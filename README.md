# 🛡️ SOC Analyst Lab – Incident Detection & Response

This repository demonstrates a **practical SOC Analyst lab**, focused on **incident detection, investigation, and response** in a controlled environment.  
All activities were conducted ethically and strictly for learning purposes.

---

## 🎯 Objective
Simulate real-world security incidents and perform:
- Detection using SIEM
- Incident investigation
- Forensic triage
- Response and mitigation
- Documentation following professional SOC standards

---

## 🧱 Lab Architecture

- **SIEM**: Wazuh
- **Firewall**: pfSense / FortiGate VM (lab)
- **Attacker**: Kali Linux
- **Victims**:
  - Windows Server / Windows 10
  - Linux (Ubuntu)
- **Tools**:
  - Nmap, Metasploit
  - Custom Bash & PowerShell scripts
  - Incident Response Toolkit (custom)

---

## 🧪 Simulated Incident Scenarios

### 🔴 Scenario 1 – Brute Force Attack (RDP / SSH)
- **Detection**: Multiple failed authentication alerts in SIEM
- **Analysis**:
  - Source IP correlation
  - User enumeration
  - Timeline reconstruction
- **Response**:
  - Account lockout
  - IP blocking
  - Log preservation
- **Outcome**: Attack contained and documented

---

### 🔴 Scenario 2 – Malware Execution
- **Detection**: Suspicious process creation
- **Analysis**:
  - Hash verification (SHA256)
  - Process inspection
  - Network connection analysis
- **Response**:
  - Host isolation
  - Evidence collection
  - IOC documentation
- **Outcome**: Malware identified and removed

---

### 🔴 Scenario 3 – Network Reconnaissance
- **Detection**: Port scanning alerts
- **Analysis**:
  - Nmap fingerprinting
  - Traffic pattern analysis
- **Response**:
  - Firewall rules applied
  - Alert tuning
- **Outcome**: Preventive controls improved

---

## 🛠️ Incident Response Toolkit
Custom automation scripts used during incidents:
- System snapshot
- Process listing and dumps
- Network connections logging
- File hash verification
- Evidence integrity validation

🔗 **Repository**: [Incident-Response-Toolkit](../Incident-Response-Toolkit)

---

## 🧭 MITRE ATT&CK Mapping

| Technique ID | Description |
|-------------|------------|
| T1110 | Brute Force |
| T1059 | Command and Scripting Interpreter |
| T1190 | Exploit Public-Facing Application |
| T1046 | Network Service Scanning |

---

## 🚨 Risk & Impact Assessment

| Incident | Severity | Impact |
|--------|----------|--------|
| Brute Force | Medium | Unauthorized access risk |
| Malware | High | Data compromise |
| Reconnaissance | Low | Information disclosure |

---

## 🛡️ Mitigation Recommendations
- Strong authentication policies
- MFA enforcement
- IDS/IPS tuning
- Patch management
- Continuous log monitoring

---

## 📜 Scope & Ethical Notice
All tests were executed in **isolated laboratory environments** using intentionally vulnerable systems.  
No unauthorized or real-world targets were involved.

---

## 🧠 Skills Demonstrated
- SOC monitoring & alert analysis
- Incident response lifecycle
- Forensic triage
- SIEM correlation
- Automation (PowerShell & Bash)
- Technical documentation

---

## 📌 Author
**Germanya Sayara**  
SOC Analyst Jr | Blue Team | Cybersecurity  
GitHub: https://github.com/germanyasayara
