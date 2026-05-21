# SOC Alert Investigation Report (L1 Simulation)

## Alert Title
Multiple Failed Login Attempts Detected (Brute Force Simulation)

---

## Objective
To investigate suspicious login activity and determine whether it is a real security threat or normal system behavior.

---

## Tools Used
- Splunk (SIEM)
- Windows Event Viewer

---

## Key Event IDs
- 4624 → Successful login
- 4625 → Failed login attempts
- 4688 → Process creation

---

## Investigation Process

### Step 1: Alert Review
- Detected multiple failed login attempts in a short time period

### Step 2: Log Analysis
- Checked failed login logs (4625)
- Checked successful login logs (4624)
- Reviewed process activity (4688)

### Step 3: Correlation
- Compared failed attempts with successful login
- Checked time sequence of events

---

## Findings

- Multiple failed login attempts detected in a short period
- A successful login occurred after repeated failures
- Pattern suggests possible brute force activity
- No suspicious process execution detected

---

## Conclusion

Severity Level: Medium

This activity is consistent with a brute force login attempt. Continuous monitoring is recommended.

---

## SOC Analyst Action

- Logged incident details
- Monitored affected user account
- No escalation required (simulation case)
