# Isaacs-SOC
Enterprise Cybersecurity Home Lab featuring Active Directory, Splunk SIEM, Sysmon, Threat Hunting, Incident Response, Vulnerability Management, and Web Application Security.
## Overview

Isaac's SOC is a professional cybersecurity home lab built to simulate a real enterprise environment using Oracle VirtualBox. The purpose of this project is to develop and demonstrate practical blue team and defensive security skills through hands-on experience.

This environment will be expanded throughout the project to include enterprise identity management, centralized logging, threat detection, incident response, vulnerability management, and web application security.

---

## Objectives

- Build a Windows Active Directory environment
- Deploy Splunk Enterprise as a SIEM
- Centralize Windows security logging
- Perform threat hunting and incident response
- Simulate real-world cyber attacks
- Detect malicious activity using Splunk
- Analyze Windows Event Logs and Sysmon
- Conduct vulnerability assessments
- Practice web application security testing
- Document every phase professionally

---

## Planned Architecture

```
Internet
      │
   pfSense Firewall
      │
----------------------------
│           │             │
DC01      WIN11      SPLUNK01
 │           │             │
 │           └─────────────┘
 │
KALI01
```

---

## Technologies

### Virtualization
- Oracle VirtualBox

### Operating Systems
- Windows Server 2025
- Windows 11 Enterprise
- Ubuntu Server
- Kali Linux

### Identity
- Active Directory
- DNS
- DHCP
- Group Policy

### Security Monitoring
- Splunk Enterprise
- Sysmon
- Windows Event Logs

### Security Tools
- Wireshark
- Nmap
- Burp Suite
- OWASP ZAP
- Nessus Essentials
- Sigma Rules

### Future Topics

- Threat Hunting
- Detection Engineering
- Digital Forensics
- Malware Analysis
- MITRE ATT&CK Mapping
- Incident Response
- Web Application Security

## Security Frameworks & Standards

- MITRE ATT&CK
- NIST Cybersecurity Framework (CSF)
- NIST SP 800-61 (Incident Response)
- OWASP Top 10
- CIS Critical Security Controls
- CVSS v3.1
- Sigma Rules
