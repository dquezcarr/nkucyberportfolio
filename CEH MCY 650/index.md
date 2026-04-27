# Certified Ethical Hacker (CEH) – Security Investigations Portfolio

## Overview

This course focused on offensive security techniques, network analysis, and vulnerability exploitation. Through hands-on labs and investigative assignments, I simulated real-world attacker methodologies to better understand how systems are compromised and how defenses can be strengthened.

---

## Investigations & Labs

### Reconnaissance Investigation: Target Footprinting & Intelligence Gathering

* **Objective:** Identify publicly available and network-level information about a target

* **Skills:** OSINT, DNS enumeration, WHOIS analysis, passive vs active reconnaissance

* **Key Findings:**

  * Identified network infrastructure, DNS records, and IP ranges using enumeration techniques 
  * Distinguished between passive and active footprinting methods used by attackers
  * Demonstrated how exposed organizational data can enable social engineering and targeted attacks

---

### Network Scanning Investigation: Port Enumeration & Service Discovery

* **Objective:** Identify live hosts, open ports, and running services on a target network

* **Tools:** Nmap (TCP, SYN, UDP scans)

* **Skills:** Network mapping, port scanning, service fingerprinting

* **Key Findings:**

  * Discovered open TCP/UDP ports and associated services through multiple scan techniques 
  * Compared SYN vs TCP connect scans to evaluate stealth vs reliability
  * Identified firewall-filtered ports and analyzed packet-level scan behavior

---

### Traffic Analysis Investigation: Packet Capture & Protocol Inspection

* **Objective:** Analyze live network traffic to understand communication behavior

* **Tools:** Wireshark

* **Skills:** Packet analysis, TCP/IP understanding, protocol filtering

* **Key Findings:**

  * Captured and analyzed TCP 3-way handshake (SYN, SYN/ACK, ACK) sequences 
  * Inspected ICMP traffic and network communication patterns
  * Used filtering techniques to isolate specific traffic flows for analysis

---

### Network Sniffing Investigation: Protocol Weakness & Data Exposure

* **Objective:** Identify vulnerabilities in unencrypted network protocols

* **Skills:** Network sniffing, ARP analysis, attack surface identification

* **Key Findings:**

  * Identified protocols vulnerable to sniffing (FTP, SMTP, HTTP) due to plaintext transmission 
  * Analyzed ARP poisoning and MAC flooding as attack techniques
  * Evaluated risks of passive vs active sniffing within network environments

---

### Authentication Attack Investigation: Credential Storage & Exploitation

* **Objective:** Analyze weaknesses in authentication systems and password storage

* **Skills:** Hash analysis, Windows authentication, privilege escalation concepts

* **Key Findings:**

  * Compared SAM-based credential storage vs domain controller authentication 
  * Analyzed password hashing methods (LM, NTLM, Kerberos) and associated risks
  * Investigated pass-the-hash attack techniques used for lateral movement

---

### Web Application Security Investigation: OWASP Top 10 Threat Analysis

* **Objective:** Identify and analyze common web application vulnerabilities

* **Skills:** Web security, vulnerability analysis, attack vectors

* **Key Findings:**

  * Evaluated critical vulnerabilities such as injection, broken access control, and misconfiguration 
  * Analyzed real-world exploitation techniques including directory traversal and CSRF
  * Demonstrated how poor input validation leads to application compromise

---

### Exploitation Investigation: SQL Injection Attack Simulation (WebGoat)

* **Objective:** Exploit input validation flaws to access restricted data

* **Tools:** WebGoat

* **Skills:** SQL injection, authentication bypass, data extraction

* **Key Findings:**

  * Successfully bypassed authentication using SQL injection payloads 
  * Retrieved sensitive user data from backend database
  * Demonstrated how improper input sanitization leads to full system compromise

---

### Web Exploitation Investigation: Cross-Site Scripting (XSS) Attack

* **Objective:** Demonstrate client-side code injection and session compromise

* **Skills:** XSS exploitation, client-side security analysis

* **Key Findings:**

  * Executed stored XSS attack resulting in persistent malicious script execution 
  * Compared stored vs reflected XSS attack vectors
  * Highlighted risks of improper input validation in web applications 

---

### Exploitation Investigation: Remote System Compromise via Metasploit

* **Objective:** Exploit known vulnerability to gain system-level access

* **Tools:** Metasploit Framework

* **Skills:** Exploitation, vulnerability analysis, shell access

* **Key Findings:**

  * Exploited MS17-010 (EternalBlue) vulnerability to gain remote shell access 
  * Established Meterpreter session on vulnerable Windows XP system
  * Demonstrated full system compromise through known unpatched vulnerability

---

## Key Skills Developed

* Network scanning and enumeration (Nmap)
* Packet analysis and traffic inspection (Wireshark)
* Web application exploitation (SQLi, XSS)
* Vulnerability analysis and exploitation (Metasploit)
* Authentication and credential attack techniques
* Offensive security methodology and attacker mindset

---

## Summary

These investigations simulate real-world attack scenarios and demonstrate the ability to identify, analyze, and exploit vulnerabilities across networks, systems, and applications. The work reflects a strong foundation in offensive security techniques and practical understanding of how attackers operate.
