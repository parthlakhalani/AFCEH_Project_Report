# Network Reconnaissance and Information Gathering

This repository contains the project report and resources for **Network Reconnaissance and Information Gathering**, conducted as part of the **Ankit Fadia Certified Ethical Hacking Program (Batch 7)**. The project demonstrates the application of ethical hacking tools and techniques to identify network vulnerabilities and gather essential information for security analysis.

---

## 📌 Project Overview

The aim of this project is to perform a comprehensive **network reconnaissance and information-gathering scan** on the target website **www.penguinbooksindia.com**. The report details the methodology, tools, and observations used to uncover potential vulnerabilities in the target system.

---

## 🛠️ Tools and Techniques

The following tools and techniques were used:
- **Ping**: Check if the target is online/offline.
- **Traceroute**: Analyze network topology and packet paths.
- **DNS Tools**: Perform WHOIS queries and gather domain-related information.
- **Nmap/Zenmap**: Identify open ports, software versions, and OS details.
- **Daemon Banner Grabbing**: Extract service and version information.
- **Security Auditing Tools**: Detect system vulnerabilities and potential exploits.

---

## 🚀 Key Steps

1. **Online Status Check**: Verified if the target system is online using `ping` and bypassed firewall blocks with advanced Nmap commands.
2. **Network Topography**: Mapped packet paths to identify key nodes using Traceroute.
3. **DNS Analysis**: Gathered WHOIS data, including admin contact details, server IPs, and domain info.
4. **Port Scanning**: Detected open ports and identified running services using Nmap.
5. **Software and OS Detection**: Extracted software details (e.g., Apache HTTPD version 2.2.22) and identified operating systems using active and passive OS fingerprinting.
6. **Vulnerability Assessment**: Leveraged security auditing tools to identify critical loopholes in the target's infrastructure.

---

## 📊 Observations

- Open Ports Detected:
  - **Port 21 (FTP)**: File Transfer Protocol
  - **Port 80 (HTTP)**: Web Service
  - **Port 554 (RTSP)**: Real-Time Streaming Protocol

- **Operating System**:
  - Microsoft Windows 7 Enterprise
  - Linux-based systems with varying configurations

- Vulnerabilities found in outdated software versions (e.g., Apache HTTPD 2.2.22).

---

## 📝 Results and Learnings

This project highlights the importance of systematic reconnaissance in ethical hacking. By utilizing a range of tools and techniques, potential vulnerabilities in networks can be identified, paving the way for better security measures. The challenges faced, such as bypassing firewalls and detecting OS configurations, emphasize the need for adaptive and strategic approaches in cybersecurity.

---

## 📁 Repository Contents

- **Report.pdf**: The complete project report detailing methodology, tools, and results.
- **Code and Commands**: Sample commands used during reconnaissance (e.g., Nmap scans, Traceroute outputs).
- **Images**: Screenshots of tool outputs, visualizing the steps and results.
- **README.md**: This overview file.

---

## 🛡️ Disclaimer

This project was conducted in a controlled environment and with permission as part of a certified ethical hacking program. Any misuse of the information or tools described herein is strictly discouraged and may lead to legal consequences.

---

## 🔗 References

- **Nmap Official Website**: [https://nmap.org](https://nmap.org)
- **Zenmap**: [https://nmap.org/zenmap/](https://nmap.org/zenmap/)
- **WHOIS Lookup Tools**: [https://whois.net](https://whois.net)

For any queries or collaboration opportunities, feel free to connect with me on [LinkedIn](https://linkedin.com/in/parth-lakhalani).
