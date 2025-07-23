# 🔐 File Integrity Monitoring (FIM) using Wazuh — SOC Analyst Real-World Lab

[![SOC Analyst Project](https://img.shields.io/badge/SOC%20Role-Learner-blue)](https://github.com/syedfaizan9920)
[![Tested On](https://img.shields.io/badge/Tested_on-Kali%20%7C%20Ubuntu-lightgrey)]()
[![Detection Engine](https://img.shields.io/badge/Detection-Wazuh%20SIEM-green)](https://wazuh.com/)
[![Project Type](https://img.shields.io/badge/Use%20Case-File%20Tampering%20Detection-critical)]()

---

## 🚀 Overview

This project demonstrates how to configure and use **File Integrity Monitoring (FIM)** using **Wazuh**, a powerful open-source SIEM platform.  
It simulates file tampering on a Linux system, monitors changes in real time, and detects malicious activity via the Wazuh Dashboard — a typical task for a SOC Analyst.

> 🧑‍💻 **Project by:** Faizanullah Syed  
> 📧 faizanulla.syed19@gmail.com

---

## 🔧 Setup Summary

- ✅ **Wazuh Manager** installed on Ubuntu server  
- ✅ **Wazuh Agent** installed on Kali Linux  
- ✅ Enabled real-time monitoring via `ossec.conf`  
- ✅ Simulated unauthorized file creation, modification & deletion  
- ✅ Detected alerts through the Wazuh FIM Dashboard

---


---

## 🧪 Simulation Flow

| Step                     | Command                                           | Purpose                        |
|--------------------------|--------------------------------------------------|--------------------------------|
| Create File              | `echo "Secret" > /root/faizan.txt`              | Simulate file creation         |
| Modify File              | `echo "Modified" >> /root/faizan.txt`           | Simulate unauthorized edit     |
| Delete File              | `rm /root/faizan.txt`                           | Simulate file deletion         |
| Detect in Wazuh Dashboard| 🔍 `filename: faizan.txt`                        | View alert logs in real-time   |

---

## 🎯 Learning Outcomes

- Set up and configured **Wazuh FIM Module**
- Simulated real-time endpoint attacks on monitored files
- Analyzed and triaged alerts as a **SOC Analyst would do in a real environment**
- Built understanding of how SIEM detects file tampering and insider threats

---


`Wazuh FIM Project` `SOC Analyst Real Lab` `File Tampering Detection`  
`Linux Security Monitoring` `Cybersecurity Blue Team Project` `SIEM Alerting Lab`  
`Hands-on Wazuh Tutorial` `Real-Time File Monitoring` `SOC Resume Project`

---

## 👤 Author

**Faizanullah Syed**  
📧 Email: faizanulla.syed19@gmail.com  
🔗 [GitHub](https://github.com/syedfaizan9920)  
🎓 Cybersecurity Enthusiast | SOC Analyst Learner  

---



