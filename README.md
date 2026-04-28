# 🛡️ SOC Analyst Home Labs

This repository contains hands-on cybersecurity labs, detection use cases, and SIEM-based investigations built using tools like **Splunk** and **QRadar**.

These labs simulate real-world attack scenarios and demonstrate detection, analysis, and response workflows.

---

## 📂 Quick Navigation

### 🔎 Splunk Detection Labs

* 🚨 [Windows Brute Force Detection](./Splunk/Bruteforce.md)
* 🔐 [Account Lockdown Detection](./Splunk/Account%20Lockdown%20Detection.md)
* 📊 [Data Exfiltration Detection](./Splunk/Data%20Exfiltration%20Detection.md)
* 🌍 [Impossible Travel Detection](./Splunk/Impossible%20Travel%20Detection.md)
* 🔁 [Lateral Movement Detection](./Splunk/Lateral%20Movement%20Detection.md)
* 🐧 [Linux Authentication Threat Detection & Investigation](./Splunk/Linux%20Authentication%20Threat%20Detection%20%26%20Investigation.md)
* ⚙️ [Linux Persistence Detection via Cron Jobs](./Splunk/Linux%20Persistence%20Detection%20via%20Cron%20Jobs.md)
* 🎯 [Multi-Stage Attack Detection](./Splunk/Multi-Stage%20Attack%20Detection.md)
* 🔓 [Password Spraying Attack](./Splunk/Password%20Spraying%20Attack.md)
* 🎣 [Phishing Attack Simulation](./Splunk/Phishing%20Attack%20Simulation.md)
* ⬆️ [Privilege Escalation Detection](./Splunk/Privilege%20Escalation.md)
* 🖥️ [Suspicious Remote Command Execution](./Splunk/Suspicious%20Remote%20Command%20Execution%20Detection.md)
* 🌐 [Web Attack Detection](./Splunk/Web%20Attack%20Detection.md)
* 🧠 [Creating Correlation Rule: Windows Brute Force](./Splunk/Creating%20Correlation%20Rule:%20Windows%20Brute%20Force%20Detection.md)

---

### 🧩 QRadar Labs

* 🚨 [Brute Force Attack](./QRADAR/Brute%20Force%20Attack.md)
* 🔐 [Distributed Password Spraying Attack](./QRADAR/Distributed%20Password%20Spraying%20Attack.md)

---

## ⭐ Featured Projects

### 🚨 Windows Brute Force Detection (Splunk)

* Detects repeated failed login attempts (Event ID 4625)
* Correlates attacker behavior using SPL
* Includes investigation workflow + screenshots

👉 [View Project](./Splunk/Bruteforce.md)

---

### 📊 Data Exfiltration Detection

* Identifies abnormal outbound traffic patterns
* Detects potential data theft scenarios
* Demonstrates SIEM correlation techniques

👉 [View Project](./Splunk/Data%20Exfiltration%20Detection.md)

---

### 🎯 Multi-Stage Attack Detection

* Tracks attacker lifecycle across multiple stages
* Combines multiple detection techniques
* Real-world SOC investigation scenario

👉 [View Project](./Splunk/Multi-Stage%20Attack%20Detection.md)

---

## 🧠 Skills Demonstrated

* SIEM: Splunk, QRadar
* Log Analysis (Windows & Linux)
* Threat Detection & Hunting
* Incident Response
* Correlation Rule Creation
* MITRE ATT&CK Mapping

---

## 📁 Repository Structure

```
Home-Labs/
├── Splunk/
│   ├── Detection Labs (.md files)
│   └── images/
│
├── QRADAR/
│   ├── Attack Simulations (.md files)
│   └── images/
```

---

## 🚀 About Me

Aspiring **SOC Analyst** with hands-on experience in:

* Security monitoring
* Threat detection
* SIEM-based investigations

Focused on building real-world detection use cases and improving blue team skills.

---

## 📌 Note

Each lab includes:

* Attack scenario
* Detection logic
* Logs / queries
* Screenshots
* Analysis

---

⭐ If you found this useful, consider starring the repo!
