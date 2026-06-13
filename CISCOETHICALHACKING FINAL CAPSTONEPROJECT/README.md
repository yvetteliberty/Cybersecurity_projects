 # 🔐EthicalHacking Final Capstone Project
## 📌Project Overview

This Final Capstone Project demonstrates practical penetration testing and vulnerability assessment skills across multiple attack vectors in a controlled lab environment. The project involved identifying vulnerabilities, exploiting misconfigurations, analyzing network traffic, and proposing remediation strategies to improve system security.

The assessment covered:

- SQL Injection Exploitation.
- Web Server Directory Listing Vulnerabilities.
- SMB Share Enumeration and Exploitation.
- Network Traffic Analysis using Wireshark.
  ## 🎯 Objectives
The goal of this project was to:
- Discover and exploit common security vulnerabilities.
- Perform reconnaissance and enumeration techniques.
- Analyze network traffic for sensitive information leakage.
- Demonstrate vulnerability assessment and reporting skills.
- Recommend security controls and remediation measures.
## Challenge 1: SQL Injection Attack
Description: 
A vulnerable web application was assessed to identify SQL Injection weaknesses that could expose user credentials.
 ## Activities Performed
- Logged into the target web application.
- Identified vulnerable input fields.
- Performed SQL Injection attacks.
- Retrieved user account information.
- Obtained password hashes.
- Cracked password hashes using password recovery tools.
- Accessed a protected system using compromised credentials.
- Retrieved the challenge flag.

 ## Skills Demonstrated
 - Web Enumeration
- Directory Discovery
- URL Manipulation
- Web Server Assessment
- Information Disclosure Analysis
## Remediation 
- Disable directory listing on web servers.
- Restrict access to sensitive directories.
- Implement proper access controls.
- Remove unnecessary files from public directories.
  
 ## Challenge 3: SMB Share Enumeration
  Description:
An SMB server was assessed to identify publicly accessible file shares.
 ## Activities Performed
- Scanned the network for SMB services.
- Enumerated available SMB shares.
- Identified anonymous access permissions.
- Navigated shared directories.
- Retrieved sensitive files.
- Downloaded and analyzed exposed content.
## Skills Demonstrated
- SMB Enumeration
- Network Reconnaissance
- Share Enumeration
- File Retrieval
- Security Misconfiguration Analysis
## Tools Used
 - Nmap
- SMBClient
- Linux Command Line
 ## Remediation 
- Disable anonymous SMB access.
- Restrict SMB access to trusted users.
- Use host-based and network firewalls.
- Apply proper file share permissions.
- Regularly audit SMB configurations.
 ## Challenge 4: PCAP Analysis and Information Disclosure
Description:
A packet capture (PCAP) file was analyzed to identify sensitive information transmitted across the network.
## Activities Performed
- Opened and reviewed packet captures.
- Identified target IP addresses.
- Extracted URLs and directories from captured traffic.
- Located sensitive files exposed over HTTP.
- Retrieved challenge information from captured network traffic.
## Skills Demonstrated
- Packet Analysis
- Network Traffic Inspection
- HTTP Analysis
- Information Gathering
- Wireshark Investigation
## Tools Used
- Wireshark
- Kali Linux
- Web Browser
## Remediation 
- Encrypt sensitive data in transit using HTTPS/TLS.
- Implement proper access controls.
- Restrict access to sensitive files.
- Apply secure authentication mechanisms.
- Regularly monitor network traffic for anomalies.
## 🛠 Tools and Technologies Used
- Kali Linux
- Nmap
- Wireshark
- SMBClient
- DVWA (Damn Vulnerable Web Application)
- Linux Terminal
- Web Browsers
## 📚 Key Skills Gained
- Vulnerability Assessment
- Penetration Testing
- Web Application Security Testing
- SQL Injection Exploitation
- Password Cracking
- SMB Enumeration
- Network Traffic Analysis
- Security Reporting
- Risk Identification
- Security Remediation Planning
  ## Screenshot of the analysis
Screenshots of filters and findings  are included in the folder.
## ⚠️ Disclaimer
This project was conducted in a controlled educational lab environment designed for cybersecurity training purposes. All activities were performed on authorized systems. 
## Cybersecurity Enthusiast | Penetration Testing | Ethical Hacking.
