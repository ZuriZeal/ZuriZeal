# 👋 Hello, I'm Zuri

🔐 Cybersecurity Student | Future SOC Analyst  
📍 Austin, Texas 

---

Welcome to my cybersecurity portfolio. 

I am currently building hands-on security projects focused on:

- Security monitoring
- Log analysis
- Threat detection
- Cloud security
- Linux system hardening

My goal is to transition into a **Security Analyst / SOC Analyst role**.

---

# 🔎 Security Portfolio

Here are some of the security projects I have completed:

### 🛡 Security Portfolio
👉 [View My Security Portfolio](https://github.com/ZuriZeal/security-portfolio)

This repository demonstrates:

- Security documentation
- Threat analysis
- Cloud security monitoring
- Incident response exercises
- System auditing

---

# 🧰 Tools & Technologies

- Linux
- AWS
- CloudWatch
- GitHub
- Markdown
- Python
- YAML
- Security Monitoring

---

# 📚 Currently Studying

- Security Operations (SOC)
- Threat Detection
- Log Analysis
- Cloud Security

---

## 🎓 Certifications & Coursework

I am currently completing the **Google Cybersecurity Professional Certificate** through Coursera.
This program focuses on hands-on security operations, threat detection, Linux security, and network defense.

Completed courses include:

* **Foundations of Cybersecurity** – 95.51%
  Certificate: https://coursera.org/share/472fec9e25b9aa4d65e33f17af496e0e

* **Tools of the Trade: Linux and SQL** – 95%
  Certificate: https://coursera.org/share/89b34a3a71d225b1ad666e12e85e25fb

* **Sound the Alarm: Detection and Response** – 88.12%
  Certificate: https://coursera.org/share/b6d3ef478e0660ef181df9950f2905f2

* **Assets, Threats, and Vulnerabilities** – 93.75%
  Certificate: https://coursera.org/share/5441e07ae673d14debdd5323391e02ca

* **Play It Safe: Manage Security Risks** – 96.43%
  Certificate: https://coursera.org/share/e436cdc3c6719fe2463d223e90fc4ccc

* **Connect and Protect: Networks and Network Security** – 99.40%
  Certificate: https://coursera.org/share/b68477e952e9a8b145ccbe9dfbf943b4

These courses cover:

- Linux security
- SQL for security analysis
- Security operations
- Threat detection and response
- Network security
- Risk management

---

## 🧠 Security Skills Matrix

| Security Domain       | Tools / Technologies                              |
| --------------------- | ------------------------------------------------- |
| Threat Detection      | auditd, CloudWatch Logs, Linux command monitoring |
| Log Analysis          | AWS CloudWatch, system logs, audit logs           |
| Detection Engineering | command monitoring, behavioral indicators         |
| Cloud Security        | AWS logging, monitoring pipelines                 |
| System Hardening      | Linux security controls, shell history protection |
| Security Operations   | SOC investigations, incident analysis             |

---

## 🚨 Featured Security Work

🔎 **SOC Command History Threat Investigation**
Detecting suspicious command execution using audit logs and shell history monitoring.
🔗 https://github.com/ZuriZeal/soc-command-history-audit

☁️ **AWS Cloud Security Monitoring Lab**
Configured CloudWatch log groups, command history auditing, and security monitoring pipelines.
🔗 https://github.com/ZuriZeal/security-portfolio

🛡 **Linux System Hardening Lab**
Implemented `auditd` rules, shell history protection, and suspicious command detection.
🔗 Included in Security Lab Projects

---
## 🔥 SOC Detection & Threat Detection Engineering

Examples of detection logic used in my security labs and investigations.

### Detect Suspicious Sudo Usage

Monitor privilege escalation attempts through audit logs.

```bash
ausearch -m USER_CMD | grep sudo
```

### Detect Reverse Shell Behavior

Identify suspicious outbound connections and shell execution patterns.

Indicators:

* Unexpected outbound connections
* Shell spawned by network processes
* High-risk command execution

### Detect Command History Tampering

Attackers often attempt to erase their tracks.

Example commands monitored:

```bash
history -c
rm -rf *
sudo su
```

Detection method:

* auditd command monitoring
* command execution logs
* CloudWatch log alerts

---

## 🕵️ Threat Hunting & Incident Investigation

Examples of proactive threat hunting performed in my security labs.

### Suspicious Privilege Escalation Hunt

Investigated abnormal privilege escalation attempts using Linux audit logs.

Indicators searched:

* Repeated sudo usage
* Unexpected root access
* Privileged command execution

Example query:

```
ausearch -m USER_CMD | grep sudo
```

---

### Reverse Shell Activity Hunt

Hunted for indicators of reverse shell behavior.

Indicators:

* Outbound connections from shell processes
* Netcat / bash network execution
* Suspicious command pipelines

Example investigation commands:

```
ps aux | grep bash
netstat -tulpn
```

---

### Command History Manipulation Hunt

Investigated attempts to erase attacker activity.

Indicators:

* History clearing commands
* Suspicious root shell access
* Destructive file operations

Example commands monitored:

```
history -c
rm -rf *
sudo su
```

---

## 🧪 Security Lab Projects

Hands-on cybersecurity labs demonstrating monitoring, logging, threat detection, and system hardening.

### 🔐 AWS Cloud Security Monitoring Lab
- Configured **AWS CloudWatch Log Groups**
- Implemented **audit logging for command history**
- Tested log forwarding and alert triggering
- Documented security monitoring workflow

### 🖥 Linux Security Hardening Lab
- Configured **auditd rules for command monitoring**
- Implemented **secure shell history controls**
- Tested detection of suspicious commands
- Verified logging visibility in monitoring tools

### 📊 SOC Log Analysis Lab
SOC command monitoring investigation.

🔗 Project:
https://github.com/ZuriZeal/soc-command-history-audit

- Practiced analyzing logs similar to a **Security Operations Center (SOC)**
- Investigated command history events
- Identified suspicious patterns
- Documented findings in markdown reports

---

## 📊 GitHub Activity

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ZuriZeal&theme=tokyonight)

![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ZuriZeal&theme=tokyonight)

![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ZuriZeal&theme=tokyonight)

---

# 🛡 Security Tools

![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)
![YAML](https://img.shields.io/badge/YAML-000000?style=for-the-badge&logo=yaml)
![AUDITD](https://img.shields.io/badge/AUDITD-Detection-blue)
![CLOUDWATCH](https://img.shields.io/badge/AWS-CloudWatch-orange)

---

# 📫 Connect With Me

GitHub Portfolio: https://github.com/ZuriZeal/security-portfolio
LinkedIn: https://www.linkedin.com/in/ivan-sweeting-6484b595/

⭐ Thank you for visiting my cybersecurity portfolio.

---

![Profile Views](https://komarev.com/ghpvc/?username=ZuriZeal&color=blue)
