# network-reconnaissance-lab
Practical network reconnaissance and port scanning lab using Nmap
# Network Reconnaissance & Port Scanning Lab

## Overview
This project documents a practical network reconnaissance exercise where I performed port scanning and service enumeration on a target system in a controlled lab environment.

The goal was to simulate how attackers identify potential entry points into a system and understand how exposed services can increase security risks.

---

## Objectives
- Perform active reconnaissance on a target machine
- Identify open ports and running services
- Analyze potential security risks based on findings
- Understand how misconfigurations can be exploited

---

## Tools Used
- Nmap
- Kali Linux

---

## Methodology

### 1. Host Discovery
I started by identifying active hosts on the network.

### 2. Port Scanning
Performed a TCP SYN scan to detect open ports:
nmap -sS 192.168.0.48


### 3. Service Enumeration
Identified services and versions running on open ports:
nmap -sV 192.168.0.48


### 4. Deeper Analysis
Analyzed exposed services to understand possible vulnerabilities and attack vectors.

---

## Findings

| Port | Service | State |
|------|--------|-------|
| 22   | SSH    | Open  |
| 80   | HTTP   | Open  |

- SSH service could be vulnerable to brute-force attacks if not secured
- HTTP service may expose web vulnerabilities depending on configuration

---

## Screenshots
<img width="1104" height="929" alt="Screenshot 2026-04-08 185455" src="https://github.com/user-attachments/assets/fa9a166f-03ba-44be-8a8d-bf889a7c121d" />


<img width="1131" height="932" alt="Screenshot 2026-04-08 190331" src="https://github.com/user-attachments/assets/44498260-0fdf-451c-96ba-68d9cb6d8ffd" />

## Key Learnings
- Open ports are potential attack surfaces
- Service version detection is critical for vulnerability assessment
- Misconfigured services increase risk exposure
- Reconnaissance is a critical phase in ethical hacking

---

## Disclaimer
This project was conducted in a controlled lab environment for educational purposes only. No unauthorized systems were targeted.

---

## 🔗 Check me out
(On linkedlin here: www.linkedin.com/in/olabode-williams-

---

## Author
Olabode Williams
Cybersecurity Analyst | Ethical Hacking | Building in Public
