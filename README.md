<div align="center">

# Hey, I'm Adam

**Cybersecurity Professional | SOC Analyst | Offensive Security Researcher**

`Winnipeg, MB` · [`securi-tee.com`](https://securi-tee.com) · [`LinkedIn`](https://linkedin.com/in/adam-takeuchi)

---

*"Acta non verba."*

---

![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-SOC_Level_1-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud_Essentials-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Linux_Foundation-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

</div>

## `>_ whoami`

Security operations professional who builds, breaks, and defends. Hands-on experience deploying SIEM/SOAR environments, simulating adversary techniques mapped to MITRE ATT&CK, writing detection rules, and responding to real-world incidents. Background in ISO 27001 compliance consulting, offensive security research, and incident response.

I don't just study security — I build labs, run attacks, write detections, and document everything.

## `>_ cat /home/adam/projects`

### 🔵 SOC Analyst Homelab — SIEM & SOAR Detection Lab
**`ELK Stack` `Sysmon` `Winlogbeat` `Atomic Red Team` `Tines` `Windows Server` `Active Directory`**

Full SOC environment built from scratch to simulate enterprise threat detection and response:
- **Architecture:** 3-VM environment — Ubuntu SIEM server, Windows Server 2019 Domain Controller, Windows 11 domain-joined endpoint
- **SIEM:** Elasticsearch + Kibana ingesting Sysmon logs via Winlogbeat from both Windows endpoints
- **Threat Simulation:** Executed 7+ MITRE ATT&CK techniques using Atomic Red Team including credential dumping (T1003.001), process injection (T1055.001), registry persistence (T1547.001), scheduled tasks (T1053.005), and masquerading (T1036.003)
- **Detection Engineering:** Built KQL detection rules for each technique with sub-60-second detection latency
- **SOAR Automation:** Tines workflow — webhook alert ingestion → email notification → VirusTotal threat enrichment → Google Sheets case logging

> 📝 **Detailed write-up coming soon on [securi-tee.com](https://securi-tee.com)**

---

### 🔴 Offensive Security Research
**`Burp Suite` `Nmap` `SQLMap` `Shodan` `Metasploit`**

Active bug bounty researcher on HackerOne targeting 10+ programs. Identifying and validating vulnerabilities including XSS, SQLi, IDOR, CSRF, SSRF, authentication bypass, and cloud misconfigurations.

---

### 🛡️ DevSecOps Security Automation Platform
**`Ruby on Rails` `TypeScript` `Go` `GitLab CI/CD`**

Full-stack security automation platform integrating SAST/dependency scanning into CI/CD pipelines. Built RESTful APIs for vulnerability management and compliance reporting with Brakeman and Bundle-Audit integration.

---

### ☁️ AWS Cloud Security Automation
**`Python` `Terraform` `AWS Lambda` `CloudWatch` `DynamoDB` `API Gateway`**

Automated cloud security assessment system using Python Lambda functions for infrastructure scanning. Infrastructure-as-code with Terraform, REST API via API Gateway, and DynamoDB for scalable storage of security findings.

---

### 🔍 Threat Intelligence Aggregator
**`Python` `Flask` `PostgreSQL` `Web Scraping`**

Flask web application aggregating threat intelligence from multiple OSINT sources via RSS feeds and security news APIs. PostgreSQL backend for efficient storage and querying of threat indicators and security advisories.

## `>_ skills --list`

```
┌──────────────────────────────────────────────────────────────────┐
│ BLUE TEAM          │ SIEM (ELK Stack), SOAR (Tines), Sysmon,    │
│                    │ Winlogbeat, Detection Engineering,          │
│                    │ Log Analysis, Incident Response,            │
│                    │ Digital Forensics, MITRE ATT&CK             │
├──────────────────────────────────────────────────────────────────┤
│ RED TEAM           │ Burp Suite, Nmap, SQLMap, Shodan,           │
│                    │ Metasploit, Atomic Red Team, OWASP Top 10   │
├──────────────────────────────────────────────────────────────────┤
│ CLOUD              │ AWS (Lambda, EC2, S3, CloudWatch,           │
│                    │ CloudFormation), Azure AD, Terraform,       │
│                    │ Docker, Kubernetes                          │
├──────────────────────────────────────────────────────────────────┤
│ PROGRAMMING        │ Python, Bash, PowerShell, JavaScript,       │
│                    │ Go, Ruby, SQL                               │
├──────────────────────────────────────────────────────────────────┤
│ SYSTEMS            │ Windows Server, Active Directory, Linux     │
│                    │ (Ubuntu/RedHat), VMware, TCP/IP, DNS        │
├──────────────────────────────────────────────────────────────────┤
│ GRC                │ ISO 27001, NIST CSF, Risk Assessment,       │
│                    │ Security Awareness Training, ISMS           │
└──────────────────────────────────────────────────────────────────┘
```

## `>_ cat /etc/certs`

| Certification | Status |
|---|---|
| CompTIA Security+ | ✅ Active (2024-2027) |
| TryHackMe SOC Analyst Level 1 | ✅ Complete |
| AWS Knowledge: Cloud Essentials | ✅ Complete |
| Linux Foundation: Intro to Kubernetes | ✅ Complete |
| eJPT (eLearnSecurity Junior Penetration Tester) | 🔄 In Progress |

## `>_ history`

- 🏆 **Long Con Infosec Conference CTF** — Scored 306/150 points (2024)
- 🔵 **Holmes CTF** — Blue team competition: memory forensics, log analysis, threat hunting (2025)
- 🥇 **Skills Manitoba IT Competition** — 5th Place (2023)
- 🎓 **MITT** — Diploma in Cyber Defence & Cloud Administration (3.8 GPA)
- 🔒 **ISO 27001 Implementation** — Led compliance initiatives for $2M+ enterprise contract
- 🦠 **Ransomware Incident Response** — Primary technical resource for active attack recovery

## `>_ ping me`

- 🌐 Blog: [securi-tee.com](https://securi-tee.com)
- 💼 LinkedIn: [adam-takeuchi](https://linkedin.com/in/adam-takeuchi)
- 📧 Email: amtakeuchi1@gmail.com

---

<div align="center">

*Building, breaking, and defending — one lab at a time.*

</div>
