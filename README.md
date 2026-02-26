<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:00FF41,100:0a0a0a&height=220&section=header&text=&fontSize=0&animation=twinkling" width="100%"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=100&lines=%24+whoami;Cybersecurity+%7C+SOC+Analyst+%7C+Offensive+Security)](https://git.io/typing-svg)

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

## `>_ cat /projects`

### 🔵 SOC Analyst Homelab — SIEM & SOAR Detection Lab
**`ELK Stack` `Sysmon` `Winlogbeat` `Atomic Red Team` `Tines` `Windows Server` `Active Directory`**

Full SOC environment built from scratch to simulate enterprise threat detection and response:
- **Architecture:** 3-VM environment — Ubuntu SIEM server, Windows Server 2019 Domain Controller, Windows 11 domain-joined endpoint
- **SIEM:** Elasticsearch + Kibana ingesting Sysmon logs via Winlogbeat from both Windows endpoints
- **Threat Simulation:** 7+ MITRE ATT&CK techniques via Atomic Red Team — credential dumping (T1003.001), process injection (T1055.001), registry persistence (T1547.001), scheduled tasks (T1053.005), masquerading (T1036.003)
- **Detection Engineering:** KQL detection rules for each technique with sub-60-second detection latency
- **SOAR Automation:** Tines workflow — webhook ingestion → email notification → VirusTotal enrichment → case logging

---

### 🔴 Offensive Security Research
**`Burp Suite` `Nmap` `SQLMap` `Shodan` `Metasploit`**

Active bug bounty researcher on HackerOne across 10+ programs. Targeting web apps, APIs, and cloud infrastructure for vulnerabilities including XSS, SQLi, IDOR, CSRF, SSRF, auth bypass, and cloud misconfigurations.

---

### 🛡️ DevSecOps Security Automation Platform
**`Ruby on Rails` `TypeScript` `Go` `GitLab CI/CD`**

Full-stack security automation platform integrating SAST/dependency scanning into CI/CD pipelines with Brakeman and Bundle-Audit for vulnerability management and compliance reporting.

---

### ☁️ AWS Cloud Security Automation
**`Python` `Terraform` `AWS Lambda` `CloudWatch` `DynamoDB` `API Gateway`**

Automated cloud security assessment system — Python Lambda functions for infrastructure scanning, Terraform IaC for reproducible deployments, REST API via API Gateway for programmatic access to findings.

---

### 🔍 Threat Intelligence Aggregator
**`Python` `Flask` `PostgreSQL`**

Flask web app aggregating threat intelligence from multiple OSINT sources via RSS feeds and security news APIs. PostgreSQL backend for storage and querying of threat indicators and advisories.

## `>_ skills --list`

```
┌─────────────────────┬────────────────────────────────────────────────┐
│ BLUE TEAM           │ ELK Stack, Tines, Sysmon, Winlogbeat,         │
│                     │ Detection Engineering, Log Analysis,           │
│                     │ Incident Response, MITRE ATT&CK               │
├─────────────────────┼────────────────────────────────────────────────┤
│ RED TEAM            │ Burp Suite, Nmap, SQLMap, Shodan,              │
│                     │ Metasploit, Atomic Red Team, OWASP Top 10     │
├─────────────────────┼────────────────────────────────────────────────┤
│ CLOUD               │ AWS (Lambda, EC2, S3, CloudWatch,              │
│                     │ CloudFormation), Azure AD, Terraform, Docker   │
├─────────────────────┼────────────────────────────────────────────────┤
│ PROGRAMMING         │ Python, Bash, PowerShell, JavaScript, Go, SQL │
├─────────────────────┼────────────────────────────────────────────────┤
│ SYSTEMS             │ Windows Server, Active Directory,              │
│                     │ Linux (Ubuntu/RedHat), VMware, TCP/IP, DNS    │
├─────────────────────┼────────────────────────────────────────────────┤
│ GRC                 │ ISO 27001, NIST CSF, Risk Assessment,         │
│                     │ Security Awareness Training, ISMS             │
└─────────────────────┴────────────────────────────────────────────────┘
```

## `>_ cat /etc/certs`

| Certification | Status |
|---|---|
| CompTIA Security+ | ✅ Active (2024-2027) |
| TryHackMe SOC Analyst Level 1 | ✅ Complete |
| AWS Knowledge: Cloud Essentials | ✅ Complete |
| Linux Foundation: Intro to Kubernetes | ✅ Complete |
| eJPT | 🔄 In Progress |

## `>_ history --recent`

🏆 **Long Con Infosec Conference CTF** — 306/150 points (2025)
🔵 **Holmes CTF** — Blue team: memory forensics, log analysis, threat hunting (2025)
🛡️ **ISO 27001 Implementation** — Led compliance for $2M+ enterprise contract
🦠 **Ransomware Incident Response** — Primary technical resource, full recovery

<div align="center">

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:00FF41,100:0a0a0a&height=120&section=footer&text=&fontSize=0" width="100%"/>

</div>
