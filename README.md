# 🏋️ Fitness Center Management System with Kiro & Amazon DocumentDB

A production-style Fitness Center Management System built using **Kiro IDE**, **Python Flask**, and **Amazon DocumentDB** to demonstrate **Spec-Driven Development** and **Agentic AI-assisted Software Engineering**.

This project digitizes traditional paper-based fitness tracking and provides a modern web application for managing clients, workout programs, body measurements, and progress analytics.

---

## 🚀 Project Overview

The application enables fitness centers and personal trainers to:

* Manage client registrations and profiles
* Create and assign workout programs
* Record body measurements and fitness assessments
* Track client progress over time
* Generate analytics and performance insights
* Store flexible fitness data using Amazon DocumentDB

---

## 🏗️ Solution Architecture

```text
Trainer / Admin
       │
       │ HTTPS
       ▼
┌────────────────────────────┐
│      Flask Web App         │
│                            │
│ • Client Registration      │
│ • Workout Management       │
│ • Progress Analytics       │
│ • Authentication           │
└─────────────┬──────────────┘
              │
              │ TLS Encrypted Connection
              ▼
┌────────────────────────────┐
│       PyMongo Driver       │
└─────────────┬──────────────┘
              │
              ▼
┌────────────────────────────┐
│        SSH Tunnel          │
└─────────────┬──────────────┘
              │
              ▼
┌────────────────────────────┐
│      EC2 Bastion Host      │
│      Public Subnet         │
└─────────────┬──────────────┘
              │
              ▼
┌────────────────────────────┐
│    Amazon DocumentDB       │
│                            │
│ • Clients Collection       │
│ • Workouts Collection      │
│ • Measurements Collection  │
└────────────────────────────┘

AWS Services:
• Amazon VPC
• EC2 Bastion Host
• Amazon DocumentDB
• CloudWatch Monitoring
• IAM Security Controls
```

---

## ☁️ AWS Architecture Components

| Component         | Purpose                                  |
| ----------------- | ---------------------------------------- |
| Flask Application | Web application backend                  |
| PyMongo           | MongoDB-compatible database driver       |
| SSH Tunnel        | Secure connectivity to private resources |
| EC2 Bastion Host  | Secure access point into AWS VPC         |
| Amazon DocumentDB | Managed NoSQL database                   |
| CloudWatch        | Monitoring and logging                   |
| IAM               | Authentication and authorization         |
| VPC               | Network isolation and security           |

---

## 💻 Technology Stack

| Category                | Technology                           |
| ----------------------- | ------------------------------------ |
| Language                | Python                               |
| Framework               | Flask                                |
| Database                | Amazon DocumentDB                    |
| Database Driver         | PyMongo                              |
| Frontend                | HTML, CSS, Bootstrap                 |
| Cloud Platform          | AWS                                  |
| Development Environment | Kiro IDE                             |
| Monitoring              | Amazon CloudWatch                    |
| Security                | TLS Encryption, IAM, VPC, SSH Tunnel |

---

## ✨ Key Features

### 👥 Client Management

* Client registration and profile management
* Fitness goals tracking
* Health notes management
* Contact information storage

### 🏋️ Workout Programs

* Custom workout creation
* Exercise management
* Sets and repetitions tracking
* Weight progression monitoring
* Rest period configuration

### 📏 Body Measurements

* Weight tracking
* BMI calculation
* Body fat monitoring
* Progress visualization

### 📊 Analytics Dashboard

* Fitness progress trends
* Goal achievement tracking
* Historical performance analysis
* Measurement comparisons

---

## 📂 Project Structure

```bash
fitness-center-management/
│
├── app.py
├── run.py
├── requirements.txt
│
├── config/
│   └── database.py
│
├── routes/
│   ├── clients.py
│   ├── workouts.py
│   └── analytics.py
│
├── models/
│   ├── client.py
│   ├── workout.py
│   └── measurements.py
│
├── templates/
├── static/
├── tests/
└── docs/
```

---

## 🔐 AWS Services Used

* Amazon DocumentDB
* Amazon EC2 (Bastion Host)
* Amazon VPC
* AWS Identity and Access Management (IAM)
* Amazon CloudWatch
* AWS Certificate Management

---

## 🧠 Kiro Development Workflow

This project follows a **Spec-Driven Development** approach:

1. Define requirements using EARS format
2. Generate architecture and design documentation
3. Create implementation plan
4. Build MVP incrementally
5. Validate with automated testing
6. Deploy and monitor

---

## 🎯 Learning Outcomes

This project demonstrates:

* Agentic AI Development with Kiro
* Spec-Driven Software Engineering
* AWS Cloud-Native Architecture
* NoSQL Database Design
* Python Web Application Development
* Secure Cloud Connectivity
* Modern DevOps Practices
* AI-Assisted Software Delivery

---

## 👨‍💻 Author

**Muhammad Faizan**

Cloud & DevOps Engineer | AWS Community Builder | Platform Engineering Enthusiast

### Certifications

* AWS Certified Cloud Practitioner
* AWS Certified Solutions Architect – Associate
* AWS Certified SysOps Administrator – Associate
* Certified Kubernetes Administrator (CKA)

### Areas of Expertise

* Cloud Infrastructure Engineering
* DevOps & Platform Engineering
* Kubernetes & Containerization
* Infrastructure as Code (Terraform)
* AWS Cloud Architecture
* AI-Powered Development Workflows

---

## ⭐ Workshop Objective

Build a real-world cloud-native Fitness Center Management System from idea to working MVP using **Kiro's AI-powered Spec-Driven Development workflow** while following modern **Cloud Engineering**, **DevOps**, and **Software Architecture** best practices.

---

## 🏷️ Tags

`AWS` `Kiro` `Amazon DocumentDB` `Python` `Flask` `DevOps` `Cloud Engineering` `Agentic AI` `NoSQL` `AWS Community Builders` `Platform Engineering`

