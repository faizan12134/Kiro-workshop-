🏋️ Fitness Center Management System with Kiro & Amazon DocumentDB

A production-style Fitness Center Management System built using Kiro IDE, Python Flask, and Amazon DocumentDB to demonstrate Spec-Driven Development and Agentic AI-assisted software engineering.

This project digitizes traditional paper-based fitness tracking and provides a modern web application for managing clients, workout programs, body measurements, and progress analytics.

Based on concepts covered in the Kiro + DocumentDB workshop study guide.

🚀 Project Overview

The application enables fitness centers and personal trainers to:

Manage client registrations and profiles
Create and assign workout programs
Record body measurements and fitness assessments
Track client progress over time
Generate analytics and performance insights
Store flexible fitness data using Amazon DocumentDB
🏗️ Architecture
Browser
   │
   ▼
Flask Web Application
   │
   ▼
Business Logic Layer
   │
   ▼
PyMongo Driver
   │
   ▼
Amazon DocumentDB
Technology Stack
Category	Technology
Language	Python
Framework	Flask
Database	Amazon DocumentDB
Driver	PyMongo
Frontend	HTML, CSS, Bootstrap
Cloud	AWS
Development	Kiro IDE
Security	TLS Encryption + SSH Tunnel
✨ Key Features
Client Management
Client registration
Fitness goals tracking
Health notes management
Contact information management
Workout Programs
Custom workout creation
Exercise tracking
Sets and reps management
Weight and rest period monitoring
Body Measurements
Weight tracking
BMI calculation
Body fat monitoring
Progress visualization
Analytics Dashboard
Fitness progress trends
Goal achievement tracking
Performance metrics
Historical comparisons
📂 Project Structure
fitness-center-management/
├── app.py
├── run.py
├── requirements.txt
├── config/
│   └── database.py
├── routes/
│   ├── clients.py
│   ├── workouts.py
│   └── analytics.py
├── models/
│   ├── client.py
│   ├── workout.py
│   └── measurements.py
├── templates/
├── static/
├── tests/
└── docs/
🔐 AWS Services Used
Amazon DocumentDB
Amazon EC2 (Bastion Host)
Amazon VPC
IAM
CloudWatch
AWS Certificate Management
🧠 Kiro Development Workflow

This project follows a Spec-Driven Development approach:

Define requirements using EARS format
Generate architecture and design documents
Create implementation plan
Build MVP incrementally
Validate with automated testing
Deploy and monitor
🎯 Learning Outcomes

This project demonstrates:

Agentic AI Development with Kiro
Spec-Driven Software Engineering
AWS Cloud-Native Architecture
NoSQL Database Design
Python Web Development
Secure Cloud Connectivity
Modern DevOps Practices
👨‍💻 Author

Muhammad Faizan
Cloud & DevOps Engineer | AWS Community Builder | Platform Engineering Enthusiast

AWS Certified
Kubernetes Certified (CKA)
DevOps & Cloud Infrastructure Specialist
AI-Powered Development Advocate
⭐ Workshop Objective

Build a real-world cloud-native application from idea to working MVP using Kiro's AI-powered development workflow while following modern DevOps and software engineering best practices.

Tags

AWS Kiro DocumentDB Python Flask DevOps Cloud Engineering Agentic AI NoSQL AWS Community Builders Platform Engineering

This version looks professional and recruiter-friendly for GitHub, LinkedIn, and AWS Community workshop repositories.
