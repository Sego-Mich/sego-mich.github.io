---
layout: single
title: "Lab Challenges"
permalink: /labs/
---

## 🔍 Web Fuzzing with FFUF
**Problem:**  
Discover hidden directories and endpoints in a web application.

**Approach:**  
Performed directory fuzzing using wordlists to uncover hidden paths and files on a target web server.

**Tools Used:**  
- FFUF  
- Kali Linux  

**Key Findings:**  
- Discovered hidden admin endpoints  
- Identified sensitive directories not publicly exposed  

**Lessons Learned:**  
- Fuzzing is critical in web reconnaissance  
- Poorly secured endpoints can expose sensitive data  

---

## 🌐 Active Directory Enumeration & Exploitation
**Problem:**  
Gain access and escalate privileges within an Active Directory environment.

**Approach:**  
Enumerated users, shares, and services, followed by privilege escalation techniques.

**Tools Used:**  
- SMB tools  
- Enumeration scripts  

**Key Findings:**  
- Weak permissions allowed lateral movement  
- Misconfigured accounts exposed credentials  

**Lessons Learned:**  
- Active Directory is a major attack surface  
- Misconfigurations are common vulnerabilities  

---

## 🛡️ OWASP Top 10 Vulnerability Analysis
**Problem:**  
Identify and understand the most critical web vulnerabilities.

**Approach:**  
Analyzed common vulnerabilities such as:
- SQL Injection  
- Cross-Site Scripting (XSS)  
- Broken Authentication  

**Tools Used:**  
- Browser Developer Tools  
- Manual testing  

**Lessons Learned:**  
- Most attacks exploit basic security flaws  
- Secure coding practices are essential  

---

## 📡 Network Attack: MAC Flooding & ARP Spoofing
**Problem:**  
Intercept and manipulate network traffic.

**Approach:**  
Simulated attacks to overload switch MAC tables and perform man-in-the-middle attacks.

**Tools Used:**  
- Wireshark  
- Ettercap  

**Key Findings:**  
- Traffic interception was possible  
- Network security weaknesses exposed  

**Lessons Learned:**  
- Layer 2 attacks are highly effective  
- Network segmentation improves security  

---

## 🔎 Log Analysis with Splunk
**Problem:**  
Detect suspicious activities from system logs.

**Approach:**  
Used SPL queries to filter and analyze logs for anomalies and attack patterns.

**Tools Used:**  
- Splunk  

**Key Findings:**  
- Identified failed login attempts  
- Detected unusual traffic patterns  

**Lessons Learned:**  
- Log analysis is key in threat detection  
- SIEM tools are essential for security monitoring  

---

## 🕵️ Passive Reconnaissance
**Problem:**  
Gather intelligence without directly interacting with the target.

**Approach:**  
Collected publicly available information such as domains, IPs, and DNS records.

**Tools Used:**  
- WHOIS  
- DNS tools  

**Lessons Learned:**  
- Valuable data can be gathered silently  
- Reconnaissance is the first phase of any attack  

---

## 💣 Exploitation with Metasploit
**Problem:**  
Exploit known vulnerabilities in a target system.

**Approach:**  
Used Metasploit modules to scan, exploit, and gain access to vulnerable systems.

**Tools Used:**  
- Metasploit Framework  

**Key Findings:**  
- Successfully gained system access  
- Demonstrated real-world exploitation techniques  

**Lessons Learned:**  
- Exploitation frameworks simplify attacks  
- Regular patching is critical  

---

## 🔐 Windows Forensics Investigation
**Problem:**  
Investigate compromised systems and recover evidence.

**Approach:**  
Analyzed system artifacts, logs, and user activity.

**Tools Used:**  
- Windows forensic tools  

**Key Findings:**  
- Identified suspicious user actions  
- Reconstructed attack timeline  

**Lessons Learned:**  
- Digital forensics is key after incidents  
- Logs provide critical evidence  