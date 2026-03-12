# Windows Security Audit Report

## Objective
This project demonstrates a basic Windows host security audit using native Windows and PowerShell tools.

## Scope
The audit reviewed the following security areas:

- System information
- Local user accounts
- Administrator privileges
- Firewall configuration
- Windows Defender status
- Running services
- Listening network ports

## Tools Used
- PowerShell
- systeminfo
- net user
- netstat
- netsh advfirewall
- Windows Defender PowerShell cmdlets

## Findings

### Finding 1 – Administrator Accounts
Local administrator group membership was reviewed to identify privileged users.

### Finding 2 – Firewall Configuration
Firewall profiles were inspected to confirm host-based network protection.

### Finding 3 – Listening Ports
Active listening ports were reviewed to identify exposed services.

## Recommendations

- Regularly review administrator accounts
- Ensure Windows Firewall remains enabled
- Monitor exposed network services

## Conclusion
This project demonstrates basic Windows host security auditing and evidence collection techniques used in incident investigation and security assessments.