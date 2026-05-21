# Windows Event Log Analysis

## Objective
To analyze Windows security logs and identify authentication and system activity patterns.

## Tools Used
- Windows Event Viewer
- Splunk
- Event IDs:
  - 4624 (Successful Login)
  - 4625 (Failed Login)
  - 4688 (Process Creation)

## Analysis Performed
- Identified successful login events (4624)
- Investigated failed login attempts (4625)
- Tracked process execution activity (4688)
- Observed user activity after authentication

## Findings
- Multiple failed login attempts may indicate brute force activity
- Successful logins often follow failed attempts
- Process creation logs show system and user activity after login

## Conclusion
This analysis demonstrates SOC L1 skills in log investigation, authentication tracking, and basic threat detection.
