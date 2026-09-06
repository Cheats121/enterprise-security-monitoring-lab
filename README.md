# Enterprise Security Monitoring Lab

Hands-on enterprise security lab featuring Active Directory, Wazuh SIEM,
endpoint monitoring, vulnerability management, and threat detection.

## Overview

This project demonstrates the implementation of a Security Information
and Event Management (SIEM) environment using Wazuh.

The lab includes:
- Windows Server 2022 running Active Directory Domain Services
- Windows 10 domain-joined client
- Ubuntu Server hosting Wazuh SIEM
- Tailscale VPN for connectivity between systems

The project focuses on centralized logging, vulnerability detection,
security configuration assessment, file integrity monitoring,
malware detection, and threat intelligence integration.

## Lab Topology

![Lab Topology](diagrams/SIEM_Topology_new.png)

## Technologies Used

- Wazuh SIEM
- Active Directory Domain Services
- Windows Server 2022
- Windows 10
- Ubuntu Server
- Tailscale
- VirusTotal API
- CIS Benchmarks
- MITRE ATT&CK

## Features Implemented

### Active Directory
- Domain controller setup
- DNS configuration
- Organizational Units
- Users and security groups
- Group Policy
- Controlled RDP access

### Security Monitoring
- File Integrity Monitoring (FIM)
- Vulnerability Detection
- Security Configuration Assessment (SCA)
- Malware Detection
- Threat Hunting

### Threat Intelligence
- VirusTotal API integration

## Detection Tests

### File Integrity Monitoring
Wazuh was configured to monitor Desktop and Downloads directories in
real time. File creation and deletion events were successfully detected.

### Vulnerability Detection
An outdated version of 7-Zip was installed to verify that Wazuh could
identify associated vulnerabilities and CVEs.

### Malware Detection
The EICAR test file was used to validate malware detection using
Windows Defender and Wazuh.

### VirusTotal Integration
VirusTotal was integrated with Wazuh to enrich file-based alerts using
file hashes.

## Results

- Centralized endpoint monitoring
- Real-time file integrity alerts
- Vulnerability detection
- Malware alert collection
- CIS security assessment
- VirusTotal threat-intelligence enrichment

## Future Work

Future work could include:
- Kali Linux attack simulations
- Custom Wazuh detection rules
- MITRE ATT&CK-mapped scenarios
- Automated response scripts

## Documentation

The full project report is available here:

[View Full Report](docs/Enterprise_Security_Monitoring_Lab.pdf)

## Authors

Joseph Emmanuel  
Varun Senthil Kumar
