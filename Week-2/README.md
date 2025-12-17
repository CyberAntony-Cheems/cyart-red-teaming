# CYART Red Teaming – Week 2

## 📌 Overview
This repository documents **Week 2 activities** of the CYART Red Teaming program.  
The focus of this week is on **advanced threat analysis, security frameworks, incident response, risk management, and hands-on security operations** using industry-standard tools.

The work includes **theoretical knowledge (PDFs)** and **practical implementations** demonstrating real-world cybersecurity workflows such as threat hunting, malware analysis, vulnerability management, incident response simulation, and a full capstone project.

---

## 🎯 Week 2 Objectives
- Understand advanced cyber threats and attacker behavior
- Apply security frameworks such as **NIST CSF** and **ISO/IEC 27001**
- Perform **threat hunting and malware analysis**
- Simulate and document **incident response workflows**
- Conduct **risk assessment and quantification**
- Execute a **full attack–detect–contain lifecycle**

---

## 🛠️ Tools & Technologies Used
- **MITRE ATT&CK Framework**
- **OWASP Threat Dragon**
- **Elastic Security / Kibana**
- **Sigma**
- **REMnux**
- **Hybrid Analysis**
- **OpenVAS**
- **DefectDojo**
- **MITRE Caldera**
- **Velociraptor**
- **Suricata**
- **Wazuh**
- **CrowdSec**
- **Metasploit**
- **Google Sheets**
- **Draw.io**

---

## 📂 Repository Structure
cyart-red-teaming/
└── Week-2/
├── 1-Theoretical-Knowledge/
│ ├── Advanced-Threat-Analysis.pdf
│ ├── Security-Frameworks.pdf
│ ├── Incident-Response-Fundamentals.pdf
│ └── Risk-Management.pdf
│
├── 2-Practical-Tasks/
│ ├── Threat-Hunting/
│ ├── Malware-Analysis/
│ ├── Vulnerability-Management/
│ ├── IR-Simulation/
│ ├── Network-Defense/
│ ├── Risk-Assessment/
│ ├── IR-Report/
│ └── Capstone/
│
└── README.md

---

## 📘 Theoretical Knowledge
The theory section covers the following topics:
- **Advanced Threat Analysis**
  - STRIDE threat modeling
  - MITRE ATT&CK framework
  - APTs, Zero-day exploits, and SolarWinds attack
- **Security Frameworks**
  - NIST Cybersecurity Framework (CSF)
  - ISO/IEC 27001
  - WannaCry ransomware case study
- **Incident Response Fundamentals**
  - IR lifecycle
  - Playbooks
  - SOC workflow
- **Risk Management**
  - Qualitative and quantitative risk assessment
  - Business Impact Analysis (BIA)
  - Annual Loss Expectancy (ALE)

All theory content is documented as **PDFs**.

---

## 🧪 Practical Tasks Summary

### 🔍 Threat Hunting
- Created Sigma rules to detect suspicious PowerShell execution
- Validated detections using Elastic Security
- Mapped detections to MITRE ATT&CK

### 🦠 Malware Analysis
- Performed static analysis using `strings` and `peframe`
- Conducted dynamic analysis using Hybrid Analysis
- Compared static and dynamic findings

### 🔎 Vulnerability Management
- Scanned Metasploitable VM using OpenVAS
- Imported findings into DefectDojo
- Prioritized vulnerabilities and created remediation plans

### 🚨 Incident Response Simulation
- Simulated phishing attack using MITRE Caldera
- Collected forensic artifacts using Velociraptor
- Identified indicators of compromise (IOCs)

### 🌐 Network Defense
- Created and tested Suricata rules to block malicious traffic
- Verified alerts and mapped to MITRE ATT&CK

### 📊 Risk Assessment
- Calculated Annual Loss Expectancy (ALE)
- Created a 5×5 likelihood vs impact risk matrix

### 📝 Incident Response Report
- Documented a phishing incident using **SANS-style report**
- Included executive summary, timeline, and mitigation steps
- Created IR workflow flowchart

### 🧠 Capstone Project
- Exploited VSFTPD backdoor using Metasploit
- Detected attack using Wazuh
- Contained attacker using CrowdSec
- Completed full incident response lifecycle

---

## 📸 Screenshots & Evidence
Each practical task includes:
- Tool execution screenshots
- Logs and alerts
- CSV exports and reports
- Flowcharts and analysis artifacts  

Screenshots are stored inside their respective practical folders.

---

## ✅ Learning Outcomes
- Practical understanding of real-world cyber attacks
- Hands-on experience with SOC and IR tools
- Ability to map attacks to MITRE ATT&CK
- Improved documentation and reporting skills
- End-to-end incident handling experience 

---
## 📌 Author
**Antony Frenish F**  
CYART Red Teaming Program
