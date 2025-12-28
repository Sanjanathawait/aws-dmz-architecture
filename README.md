AWS DMZ Architecture – Minor & Major Project
📌 Overview

This repository contains both the Minor Project and Major Project completed as part of the academic curriculum. The project focuses on designing a secure DMZ-based cloud architecture on Amazon Web Services (AWS) and extending it with real-world cyber-attack simulation, detection, and security monitoring.

The work follows a Red Team (Attack) and Blue Team (Detect & Secure) methodology to demonstrate practical cloud security concepts.

🧩 Project Breakdown
✅ Minor Project – AWS DMZ Architecture (Completed)
🔹 Description

The Minor Project focuses on the design and deployment of a DMZ-based cloud infrastructure on AWS. The objective was to implement secure network segmentation and controlled internet access using AWS networking components.

🔹 Key Features

Secure network segmentation using DMZ architecture

Deployment of EC2 instances in public (DMZ) and private subnets

Controlled internet access using Internet Gateway and Route Tables

Web server hosting and validation

Complete documentation with screenshots and architecture explanation

🔹 Implementation Highlights

VPC creation with CIDR planning

Public & private subnet configuration

Route table association for DMZ and internal network

Security group rules for controlled access

Apache Web Server deployment on EC2

📄 Minor Project Report
minor-project/Minor_Project_Report.pdf

📸 Screenshots
minor-project/screenshots/

🚀 Major Project – Attack, Detect & Secure the Environment (AWS) (Completed)
🔹 Description

The Major Project extends the Minor Project by adding real-world attack simulation, detection, and security monitoring. A Red Team attacker performs unauthorized SSH access attempts on a victim EC2 instance, while a Blue Team monitors and detects these attacks using AWS CloudWatch as a SIEM solution.

🔹 Major Project Objectives

Simulate SSH-based cyber-attacks in a cloud environment

Generate real authentication and security logs

Detect attacks using centralized logging (SIEM)

Analyze logs to identify Indicators of Compromise (IoCs)

Demonstrate before-and-after security visibility

🔹 Major Project Features

Red Team attack simulation (SSH brute-force / invalid user attempts)

Blue Team monitoring using AWS CloudWatch Logs

CloudWatch Agent configuration on EC2

Centralized log collection and analysis

Practical SIEM implementation using AWS-native services

🔹 Detection & Monitoring

SSH authentication log analysis (/var/log/auth.log)

Detection of:

Invalid user attempts

Failed password authentication

Suspicious connection behavior

Log analysis using CloudWatch Log Groups and Log Streams

📄 Major Project Report
major-project/Attack_Detect_Secure_Environment_AWS_Report.pdf

📸 Screenshots
major-project/screenshots/

🧰 Technologies Used
Cloud & Networking

Amazon Web Services (AWS)

VPC

Public & Private Subnets (DMZ & Internal)

Route Tables & Internet Gateway

Compute & OS

Amazon EC2

Ubuntu Linux

Kali Linux (Attacker VM)

Security & Monitoring

AWS IAM

AWS CloudWatch

AWS CloudWatch Agent

SSH Protocol

Web Services (Minor Project)

Apache Web Server

🎓 Academic Information

Author: Sanjana Thawait

Course: B.Tech CSE (Cybersecurity)

ERP: 6604710

Semester: 5th

College: Rungta College of Engineering and Technology

Academic Year: 2025–2026

📊 Project Status

Minor Project: ✅ Submitted

Major Project: ✅ Completed

⚠️ Disclaimer

This repository is created strictly for academic and educational purposes. All attack simulations were conducted in a controlled environment on resources owned by the author. No real systems or external networks were harmed.

🏁 Final Note

This repository demonstrates a complete cloud security lifecycle:
Design → Deploy → Attack → Detect → Secure

---

## Project Status
- Minor Project: ✅ Submitted
- Major Project: ⏳ In Progress
