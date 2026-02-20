# Cybersecurity Detection Labs  
Hands on Security Operations projects focused on log analysis, network traffic investigation, and malware threat intelligence research.

---

## 📖 Overview

This repository documents practical cybersecurity detection labs designed to simulate real-world SOC workflows.  

The projects demonstrate:

- Windows authentication monitoring
- Privilege escalation tracking
- Account lockout investigation
- Network packet analysis
- DNS and TCP traffic inspection
- Malware hash intelligence validation
- Multi-engine threat detection analysis

Each lab includes screenshots, event breakdowns, technical explanation, and security analysis reasoning.

---

## 🔍 Project Areas

### 🟢 1. Windows Event Monitoring (Wazuh SIEM)

- Event ID 4625 – Failed Logon  
- Event ID 4624 – Successful Logon  
- Event ID 4740 – Account Lockout  
- Event ID 4732 – Added to Administrators  
- Event ID 4733 – Removed from Administrators  

Skills Demonstrated:
- Authentication failure investigation  
- Privilege escalation detection  
- Timeline correlation  
- Log field interpretation  
- Security event triage  

---

### 🔵 2. Network Traffic Analysis (Wireshark)

- DNS Query inspection (UDP 53)
- Transaction ID analysis
- TCP handshake & ACK packet review
- Source and destination IP tracking
- Packet byte-level inspection
- Header field analysis (TTL, Flags, Length)

Skills Demonstrated:
- Packet-level analysis  
- Network flow interpretation  
- DNS resolution breakdown  
- TCP session understanding  

---

### 🔴 3. Malware Threat Intelligence Investigation

- File hash lookup
- Multi-engine detection comparison
- Threat family identification
- Vendor classification review
- Behavioral tagging analysis

Example Finding:
- 58/72 vendors flagged file as malicious
- Threat category: Trojan / Backdoor
- Family lab
