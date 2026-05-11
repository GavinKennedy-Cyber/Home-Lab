# 🏗️ Gavin's Cybersecurity Home Lab

This repository documents the architecture, configuration, and security testing performed within my personal home lab. This environment serves as a sandbox for learning enterprise security protocols, incident response, and cloud infrastructure management.

## 🖥️ Lab Architecture
- **Hypervisor:** Oracle VirtualBox / VMware Workstation
- **Operating Systems:** - **Attack:** Kali Linux (Metasploit, Nmap, Burp Suite)
  - **Defense:** Windows Server 2022 (Active Directory), Ubuntu Server
  - **Endpoints:** Windows 10/11 (Hardened for testing)
- **Cloud Integration:** AWS Free Tier for CloudWatch and GuardDuty monitoring

## 🛡️ Key Projects & Configurations
- **Active Directory Hardening:** Implemented Group Policy Objects (GPOs) to enforce password complexity and disable non-essential services.
- **Network Segmentation:** Configured internal virtual networks to isolate vulnerable "target" machines from the host machine.
- **Vulnerability Scanning:** Conducted regular asset discovery and port auditing using Nmap.

## 📚 Currently Learning
- Configuring **Wazuh** for centralized log management (SIEM).
- Preparing for **CompTIA Security+** by simulating exam objectives in this lab environment.

---
*Disclaimer: All activities in this lab are performed in a controlled, legal, and ethical manner for educational purposes.*
