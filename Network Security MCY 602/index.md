# Network Security – Firewall, VPN & Threat Defense Investigations

## Overview

This course focused on securing network infrastructure through firewall configuration, intrusion detection, VPN deployment, and attack simulation. Through hands-on investigations, I analyzed how networks are designed, defended, monitored, and tested against real-world threats.

---

## Security Investigations

### Network Architecture Investigation: Secure Topology Design & Traffic Validation

* **Objective:** Design and validate a secure network architecture

* **Tools:** pfSense, Wireshark

* **Skills:** Network segmentation, topology design, traffic analysis

* **Key Findings:**

  * Designed a multi-host network with segmented communication paths 
  * Validated connectivity using ICMP testing and packet captures
  * Identified failed and successful communication flows to verify segmentation controls

---

### Firewall Configuration Investigation: pfSense Interface & Rule Implementation

* **Objective:** Configure and validate firewall interfaces and rules

* **Tools:** pfSense

* **Skills:** Firewall configuration, interface management, rule enforcement

* **Key Findings:**

  * Configured LAN, WAN, and DMZ interfaces within pfSense 
  * Implemented firewall rules to control inbound and outbound traffic
  * Verified connectivity using ICMP requests across network segments

---

### Endpoint Firewall Investigation: Windows Defender Firewall Hardening

* **Objective:** Secure host-level network access using firewall rules

* **Tools:** Windows Defender Firewall

* **Skills:** Endpoint security, rule configuration, service exposure control

* **Key Findings:**

  * Identified blocked HTTP access before rule configuration 
  * Enabled inbound firewall rules to allow web traffic
  * Validated successful service access post-configuration

---

### Threat Simulation Investigation: Network Compromise & Defense (Infection Monkey)

* **Objective:** Simulate and analyze a network-based attack

* **Tools:** Infection Monkey, antivirus tools

* **Skills:** Threat simulation, incident response, remediation

* **Key Findings:**

  * Successfully simulated exploitation of a vulnerable web server 
  * Observed lateral movement and file transfer behavior across systems
  * Applied remediation steps including malware removal and system patching

---

### Network Monitoring Investigation: Logging & Intrusion Detection (Snort)

* **Objective:** Monitor network activity and detect suspicious behavior

* **Tools:** pfSense Logs, Snort IDS, Kiwi Syslog

* **Skills:** Log analysis, intrusion detection, alert monitoring

* **Key Findings:**

  * Captured and analyzed firewall logs for network activity 
  * Configured Snort IDS to detect ICMP-based alerts
  * Forwarded logs to centralized syslog server for monitoring

---

### VPN Infrastructure Investigation: Secure Remote Access with pfSense

* **Objective:** Deploy and configure a secure VPN server

* **Tools:** pfSense, IPsec, OpenVPN

* **Skills:** VPN configuration, encryption, secure tunneling

* **Key Findings:**

  * Configured IPsec VPN tunnels and certificate authorities 
  * Implemented firewall rules to allow VPN traffic
  * Validated secure communication between remote systems

---

### Secure Communication Investigation: VPN Client Configuration & Traffic Analysis

* **Objective:** Analyze secure vs non-secure communication over a VPN

* **Tools:** Windows VPN Client, Wireshark

* **Skills:** Traffic analysis, encryption validation, secure communications

* **Key Findings:**

  * Configured VPN client and verified encrypted communication using AES-256 
  * Compared plaintext vs encrypted traffic in Wireshark captures
  * Identified sensitive data exposure in non-secure protocols

---

### Penetration Testing Investigation: Firewall Exploitation & Vulnerability Analysis

* **Objective:** Identify vulnerabilities through controlled penetration testing

* **Tools:** pfSense, vulnerability scanner

* **Skills:** Vulnerability scanning, penetration testing, risk analysis

* **Key Findings:**

  * Conducted network scans identifying multiple vulnerabilities 
  * Analyzed firewall rule configurations for exposure risks
  * Evaluated remediation strategies to strengthen network defenses

---

## Key Skills Developed

* Firewall configuration and rule management (pfSense, Windows Defender)
* Network segmentation and topology design
* VPN deployment and secure communication analysis
* Intrusion detection and log analysis (Snort, Syslog)
* Threat simulation and incident response
* Vulnerability scanning and penetration testing

---

## Summary

These investigations demonstrate the ability to design, secure, monitor, and test network environments against real-world threats. The work reflects practical experience in defensive security, threat detection, and network hardening aligned with SOC and network security operations.

