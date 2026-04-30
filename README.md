# Incident Response & Forensic Analysis

## Overview
This project investigates a simulated cyber incident involving malware execution, privilege escalation, and data exfiltration.

## Incident Summary
- Initial access via phishing email
- Malicious file: patch.exe
- Privilege escalation via admin account
- Data exfiltration from file server
- Remote access via TOR node

## Key Indicators of Compromise (IoCs)
- Malicious IP: 183[.]81[.]169[.]238
- TOR exit node: 171[.]25[.]193[.]25
- File: secret-information-results-passwords.txt
- Suspicious account: Administrat0r

## Attack Techniques (MITRE ATT&CK)
- T1136 – Create Account
- T1059 – PowerShell Execution
- T1041 – Data Exfiltration
- T1078 – Valid Accounts

## Attack Flow
1. Phishing email delivered malware
2. Admin executes malicious file
3. Persistence established
4. Data exfiltrated
5. Access sold on dark web

## Remediation
- Isolate infected hosts
- Remove malware and persistence
- Reset credentials
- Apply patches
- Implement MFA
- Enable monitoring

## Key Learning
Most breaches start with human error and escalate due to poor access control.
