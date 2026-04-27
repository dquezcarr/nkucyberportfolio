# Web Security – Application Threat & Vulnerability Investigations

## Overview

This course focused on identifying, analyzing, and exploiting web application security weaknesses in controlled lab environments. These investigations demonstrate practical experience with reconnaissance, attack surface mapping, vulnerability scanning, authentication risks, access control flaws, SQL injection, and secure application architecture.

---

## Security Investigations

### Web Security Lab Environment Investigation: Kali, Metasploit & VM Setup

* **Objective:** Configure the virtual lab environment used for web security testing

* **Tools:** Kali Linux, Metasploit, Armitage, MSFVenom, NASM

* **Key Findings:**

  * Configured Kali, Metasploitable, and pfSense lab access
  * Verified VM networking and connectivity
  * Initialized Metasploit database and supporting tools

---

### Reconnaissance Investigation: Intelligence Gathering & Attack Surface Mapping

* **Objective:** Gather target information and identify exposed services

* **Tools:** WHOIS, Netcraft, nslookup, Nmap, Metasploit

* **Key Findings:**

  * Collected domain, registrar, DNS, hosting, and technology information
  * Identified open ports and exposed services on the target VM
  * Imported scan results into Metasploit for further analysis

---

### Client-Side Security Investigation: Web Technologies & Attack Surface Analysis

* **Objective:** Analyze client-side data handling and web application attack surfaces

* **Skills:** Client-side controls, server-side validation, HTTPS, secure data handling

* **Key Findings:**

  * Explained why client-side validation cannot be trusted alone
  * Identified risks with cookies, hidden fields, scripts, and exposed client data
  * Connected intelligence gathering to stronger security analysis

---

### Vulnerability Scanning Investigation: Nessus & Metasploit Analysis

* **Objective:** Identify and analyze vulnerabilities in a target VM

* **Tools:** Nessus, Metasploit

* **Key Findings:**

  * Installed and configured Nessus on Kali
  * Scanned the target VM and identified critical vulnerabilities
  * Imported Nessus results into Metasploit for follow-up analysis

---

### Authentication & Session Management Investigation

* **Objective:** Analyze insecure authentication and session handling behavior

* **Skills:** Session cookies, GET vs POST, HTTPS, credential exposure

* **Key Findings:**

  * Identified credential exposure in URL query strings
  * Analyzed cookie scope using domain and path attributes
  * Explained risks of transmitting authentication data over HTTP

---

### Access Control Investigation: UID Manipulation & Authorization Testing

* **Objective:** Test whether application access controls rely on unsafe user-controlled identifiers

* **Skills:** Access control testing, IDOR analysis, MAC/DAC/RBAC/ABAC comparison

* **Key Findings:**

  * Described how changing UID values can reveal broken access control
  * Compared common access control models
  * Identified horizontal access control testing methods

---

### Web Application Penetration Test Case Study: Banking Environment

* **Objective:** Build a penetration testing approach for a financial web application

* **Skills:** OWASP, PTES, threat modeling, executive reporting

* **Key Findings:**

  * Defined a banking-focused web application testing methodology
  * Identified attack surfaces such as APIs, login flows, databases, and file servers
  * Proposed deliverables including executive summary, remediation roadmap, and technical findings

---

### Data Store Attack Investigation: SQL Injection & Social Engineering

* **Objective:** Analyze how data store attacks succeed and how they can be mitigated

* **Tools:** Hacksplaining SQL Injection tutorial

* **Key Findings:**

  * Completed SQL injection tutorial analysis
  * Explained why the exploitation attempt worked
  * Identified mitigation strategies to remove the vulnerability

---

### Application Architecture Investigation: Information Disclosure & LAMP Risk

* **Objective:** Analyze how error messages and architecture choices affect application security

* **Skills:** Information disclosure analysis, LAMP architecture risk, defense-in-depth

* **Key Findings:**

  * Identified leaked usernames, server paths, and backend details from error messages
  * Explained how single-server LAMP architecture increases breach impact
  * Recommended stronger separation between application and database layers

---

## Key Skills Developed

* Web application reconnaissance and attack surface mapping
* Vulnerability scanning with Nessus
* Metasploit-based service and vulnerability analysis
* Authentication and session management review
* Access control and IDOR testing concepts
* SQL injection analysis and remediation
* Secure web architecture and information disclosure analysis

---

## Summary

These investigations demonstrate the ability to assess web applications from both offensive and defensive perspectives. The work reflects practical skills in reconnaissance, vulnerability discovery, access control testing, authentication analysis, and secure architecture review.

