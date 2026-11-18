Metasploitable 2 – Penetration Testing Lab

Project Overview

A practical cybersecurity project focused on Vulnerability Assessment and Penetration Testing using Kali Linux and Metasploitable 2.

Lab Environment

- Attacker Machine: Kali Linux
- Target Machine: Metasploitable 2
- Attacker IP: 10.0.2.15
- Target IP: 10.0.2.16

Tools Used

- Nmap – Network Scanning
- Metasploit – Vulnerability Exploitation
- Hydra – Password Security Testing
- Netcat – Network Connections
- Wireshark – Network Traffic Analysis

Practical Activities

1. Network reconnaissance and port scanning.
2. Service version detection using Nmap.
3. FTP backdoor vulnerability testing.
4. SSH password security testing.
5. Telnet traffic analysis using Wireshark.
6. Vulnerability identification and remediation.

Security Findings

- Outdated FTP service (vsftpd 2.3.4).
- Weak default credentials.
- Insecure Telnet communication.
- Exposed root shell service on port 1524.

Remediation

- Disable Telnet and use SSH.
- Replace vulnerable software with supported versions.
- Enforce strong passwords.
- Disable unnecessary services.
- Apply firewall restrictions.

Learning Outcomes

- Understanding network reconnaissance.
- Learning vulnerability assessment.
- Understanding exploitation techniques.
- Analyzing network traffic.
- Understanding cybersecurity defense strategies.

Disclaimer

This project was conducted in an authorized and isolated virtual lab environment for educational purposes only.

Created by: Hariharan.M