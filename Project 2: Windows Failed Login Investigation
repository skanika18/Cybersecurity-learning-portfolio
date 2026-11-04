# Project 2: Windows Failed Login Investigation

## Objective
To identify and investigate unsuccessful Windows login attempts.

## Tool Used
Windows Event Viewer

## Event Details
- Log: Windows Security
- Event ID: 4625
- Account: SOC-Lab
- Logon Type: 2 (Interactive)
- Failure Reason: Unknown username or bad password
- Status: 0xC000006D
- Sub Status: 0xC000006A
- Source Address: 127.0.0.1
- Process: svchost.exe

## Investigation Steps
1. Opened Windows Event Viewer.
2. Navigated to Windows Logs → Security.
3. Filtered the Security log for Event ID 4625.
4. Opened the failed login event.
5. Examined the account, logon type, failure reason and source address.
6. Identified that the failed attempt was generated during controlled testing using the SOC-Lab account.

## Findings
The login attempt failed because of an incorrect password.

Logon Type 2 indicates an interactive login attempt. The source address 127.0.0.1 indicates the local computer.

## Conclusion
The event was expected and generated intentionally for this lab. No evidence of malicious activity was established from this event alone.

## Skills Practised
- Windows Security Event Logs
- Event ID 4625
- Authentication failure analysis
- Logon Type identification
- Basic security event investigation
