# Cloud Computing – AWS Security & Infrastructure Investigations

## Overview

This course focused on deploying, managing, and analyzing cloud infrastructure using AWS services. Through hands-on investigations, I explored how cloud environments are built, scaled, and secured while evaluating performance, cost, and availability tradeoffs.

---

## Investigations & Labs

### Infrastructure Deployment Investigation: EC2 Instance Provisioning & Network Configuration

* **Objective:** Deploy and configure a cloud-hosted server using AWS CLI

* **Tools:** AWS CLI, EC2, Security Groups

* **Skills:** Cloud provisioning, network configuration, access control

* **Key Findings:**

  * Configured AWS CLI with IAM credentials and deployed EC2 instances 
  * Created and applied security groups allowing controlled SSH (22) and HTTP (80) access
  * Demonstrated how improper security group rules could expose systems to the internet

---

### Cloud Storage Investigation: S3 Bucket Configuration & Public Access Risk

* **Objective:** Deploy and manage cloud object storage while analyzing access risks

* **Tools:** AWS S3, AWS CLI

* **Skills:** Cloud storage, access control, data exposure analysis

* **Key Findings:**

  * Created S3 buckets and uploaded web content using CLI commands 
  * Configured bucket policies to allow public access
  * Identified risks of publicly exposed storage and improper access configurations

---

### Data Persistence Investigation: EBS Volume Management & Backup Integrity

* **Objective:** Analyze persistent storage and backup strategies in cloud environments

* **Tools:** AWS EBS, Snapshots

* **Skills:** Storage management, backup validation, system recovery

* **Key Findings:**

  * Created and attached EBS volumes to EC2 instances 
  * Mounted and formatted storage within Linux environments
  * Created snapshots to validate backup and recovery processes

---

### Load Distribution Investigation: High Availability with Elastic Load Balancing

* **Objective:** Evaluate traffic distribution across multiple cloud instances

* **Tools:** AWS ELB, EC2, CloudWatch

* **Skills:** Load balancing, availability design, monitoring

* **Key Findings:**

  * Deployed load balancer to distribute traffic across multiple instances 
  * Verified traffic routing between instances through repeated requests
  * Monitored system performance and availability using CloudWatch metrics 

---

### Scalability Investigation: Auto Scaling & Resource Optimization

* **Objective:** Analyze dynamic scaling of cloud infrastructure under load

* **Tools:** AWS Auto Scaling, CloudWatch

* **Skills:** Performance tuning, automation, cloud elasticity

* **Key Findings:**

  * Created auto scaling groups with defined min/max capacity 
  * Triggered scale-up events using CPU stress testing
  * Observed real-time scaling behavior based on CloudWatch alarms

---

### Content Delivery Investigation: CloudFront CDN Deployment & Performance Optimization

* **Objective:** Analyze content delivery optimization using a CDN

* **Tools:** AWS CloudFront, S3

* **Skills:** CDN configuration, caching, performance optimization

* **Key Findings:**

  * Deployed CloudFront distribution with S3 as origin 
  * Analyzed distribution deployment lifecycle (InProgress → Deployed)
  * Evaluated how CDN reduces latency and improves global availability 

---

### Performance & Cost Analysis Investigation: EC2 vs S3 Web Hosting

* **Objective:** Compare performance and cost between cloud hosting solutions

* **Tools:** Apache Benchmark (ab), AWS Pricing Calculator

* **Skills:** Performance testing, cost analysis, cloud architecture evaluation

* **Key Findings:**

  * Conducted performance tests using concurrent request simulations (50–250 users) 
  * Measured response times for EC2-hosted vs S3-hosted web applications
  * Evaluated tradeoffs between cost efficiency and performance
  * Determined optimal hosting strategy based on workload requirements

---

## Key Skills Developed

* AWS infrastructure deployment (EC2, S3, EBS)
* Cloud security configuration and risk analysis
* Load balancing and high availability design
* Auto scaling and performance optimization
* Cloud monitoring and metrics analysis (CloudWatch)
* Cost-performance tradeoff analysis in cloud environments

---

## Summary

These investigations demonstrate the ability to design, deploy, and analyze cloud infrastructure in AWS environments. The work highlights both operational knowledge and security awareness, with a focus on performance, scalability, and risk management in modern cloud systems.

