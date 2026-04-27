# Cloud Security – AWS Security Investigations

## Overview

This course focused on securing cloud infrastructure using AWS-native security services. Through a series of hands-on investigations, I analyzed identity management, network security, threat detection, logging, encryption, and compliance within cloud environments.

---

## Investigations & Assignments

### Identity & Access Control Investigation: IAM Hardening & Least Privilege Enforcement

* **Objective:** Strengthen identity security and enforce access control policies

* **Tools:** AWS IAM, AWS CLI

* **Skills:** Identity security, least privilege, credential protection

* **Key Findings:**

  * Implemented strong password policies enforcing complexity and rotation 
  * Created IAM users and groups to avoid root account usage 
  * Reduced risk of unauthorized access through structured permission management

---

### Network Segmentation Investigation: VPC Architecture & Access Control Design

* **Objective:** Design and secure cloud network boundaries

* **Tools:** AWS VPC, Security Groups, NACLs

* **Skills:** Network segmentation, access control, architecture design

* **Key Findings:**

  * Built a VPC with subnets, routing tables, and internet gateway 
  * Analyzed differences between Security Groups (instance-level) and NACLs (subnet-level) 
  * Demonstrated layered network security controls to restrict unauthorized access 

---

### Vulnerability Assessment Investigation: EC2 Security Analysis with AWS Inspector

* **Objective:** Identify vulnerabilities and misconfigurations in cloud instances

* **Tools:** AWS Inspector, EC2

* **Skills:** Vulnerability management, system hardening, CVE analysis

* **Key Findings:**

  * Deployed EC2 instance and conducted automated vulnerability scans 
  * Installed and configured Inspector agent for continuous assessment
  * Analyzed findings to improve system security posture 

---

### Threat Detection Investigation: AWS GuardDuty & Threat Intelligence Simulation

* **Objective:** Detect and analyze malicious activity in cloud environments

* **Tools:** AWS GuardDuty, S3, Threat Intel Sets

* **Skills:** Threat detection, alert analysis, SOC-style investigation

* **Key Findings:**

  * Enabled GuardDuty and created detectors for threat monitoring 
  * Simulated malicious activity using custom threat intelligence lists
  * Evaluated detection capabilities for suspicious IP behavior

---

### Log Analysis Investigation: ELB & CloudFront Logging for Security Monitoring

* **Objective:** Analyze logs to identify traffic patterns and anomalies

* **Tools:** AWS ELB Logs, CloudFront Logs, S3

* **Skills:** Log analysis, anomaly detection, monitoring

* **Key Findings:**

  * Configured ELB logging to capture incoming traffic data 
  * Enabled CloudFront logging for CDN traffic visibility 
  * Identified key log fields (status codes, request paths, edge locations) for analysis

---

### Data Protection Investigation: Encryption & Key Management with AWS KMS

* **Objective:** Secure cloud storage using encryption techniques

* **Tools:** AWS KMS, EFS

* **Skills:** Encryption, key management, data protection

* **Key Findings:**

  * Created KMS keys and applied encryption to EFS storage 
  * Ensured data protection at rest through managed encryption services
  * Demonstrated secure storage architecture for sensitive data

---

### Cloud Storage Security Investigation: Data Protection Strategies & Risk Analysis

* **Objective:** Evaluate security risks across AWS storage services

* **Tools:** AWS S3, EBS, EFS

* **Skills:** Data security, encryption strategy, risk analysis

* **Key Findings:**

  * Analyzed risks of data at rest and in transit 
  * Evaluated encryption strategies and secure data handling practices
  * Identified best practices to prevent data breaches and unauthorized access

---

### Cloud Security Architecture Investigation: Security Hub & Centralized Monitoring

* **Objective:** Design a secure cloud architecture with centralized visibility

* **Tools:** AWS Security Hub, GuardDuty, AWS Config

* **Skills:** Security architecture, compliance, monitoring

* **Key Findings:**

  * Integrated multiple AWS security services for centralized monitoring 
  * Applied shared responsibility model to cloud security design
  * Demonstrated layered defense across compute, network, and storage

---

## Key Skills Developed

* Cloud identity & access management (IAM)
* Network security & segmentation (VPC, NACLs, Security Groups)
* Threat detection & monitoring (GuardDuty, Security Hub)
* Vulnerability assessment (AWS Inspector)
* Log analysis & SIEM-style investigation
* Encryption & data protection (KMS, EFS, S3)
* Cloud security architecture & compliance

---

## Summary

These investigations demonstrate the ability to secure AWS environments through identity management, network controls, threat detection, and data protection strategies. The work emphasizes real-world cloud security practices aligned with SOC operations, incident detection, and risk mitigation.

