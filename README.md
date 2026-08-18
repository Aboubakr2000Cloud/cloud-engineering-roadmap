# Cloud Engineering Portfolio

## Overview

A collection of production-style cloud infrastructure, automation, security, and DevOps projects built to demonstrate practical cloud engineering capabilities.

The portfolio spans AWS infrastructure, Terraform, containerized applications, CI/CD, observability, security hardening, serverless architectures, Python automation, and full-stack cloud systems.

Projects are built as standalone, reproducible systems with infrastructure managed as code, automated deployment workflows, documented architecture, and real-world troubleshooting and validation.

The projects intentionally progress from focused infrastructure and automation systems toward increasingly complex, production-style architectures.

---

## ⭐ Featured Projects

### [Cloud Cost Intelligence Platform](https://github.com/Aboubakr2000Cloud/cloud-cost-intelligence)

A production-style multi-layer AWS platform that collects and analyzes cloud cost data, detects spending anomalies, sends automated alerts, and exposes the results through a web dashboard.

The platform combines real AWS Cost Explorer data with clearly disclosed synthetic demonstration data to provide meaningful historical cost analysis even when real account usage is limited.

**Architecture & Capabilities:**

* AWS Cost Explorer cost collection
* 90 days of synthetic cost data
* Multi-service cost analysis
* Automated anomaly detection
* SNS anomaly alerts
* ECS Fargate API
* RDS MySQL
* Lambda-based ingestion and analysis
* EventBridge scheduling
* S3 + CloudFront frontend delivery
* CloudWatch monitoring and alarms
* Secrets Manager + KMS
* IAM least-privilege design
* Modular Terraform infrastructure
* GitHub Actions CI/CD
* End-to-end smoke testing
* Automatic dashboard refresh

**Tech Stack:** Terraform, AWS ECS Fargate, Lambda, RDS MySQL, EventBridge, SNS, S3, CloudFront, CloudWatch, Cost Explorer, Secrets Manager, KMS, IAM, Docker, GitHub Actions, Python

---

### [ECS Weather Platform — Security Hardening](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-secured)

The final security-hardened evolution of a production-style containerized AWS platform.

The system was progressively extended with automated CI/CD, observability, and security controls while maintaining application availability and database connectivity.

**Security & Infrastructure:**

* IAM least-privilege policies
* Customer-managed KMS encryption
* Secrets Manager
* Systems Manager Parameter Store
* CloudTrail auditing
* GuardDuty
* TruffleHog secret scanning
* ECS Fargate
* Amazon ECR
* RDS MySQL
* Application Load Balancer
* CloudWatch monitoring
* GitHub Actions CI/CD

**Tech Stack:** Terraform, AWS ECS, ECR, RDS, ALB, KMS, IAM, Secrets Manager, Parameter Store, CloudTrail, GuardDuty, Docker, GitHub Actions, CloudWatch

**Platform evolution:**

[Initial ECS platform](https://github.com/Aboubakr2000Cloud/ecs-weather-platform) → [CI/CD](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-cicd) → [Monitoring](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-with-monitoring) → **Security Hardening**

---

### [Weather Serverless Platform](https://github.com/Aboubakr2000Cloud/weather-serverless-platform)

A production-style event-driven AWS application demonstrating serverless architecture and managed cloud services.

**Architecture:**

* Lambda functions for API, collection, and processing
* API Gateway HTTP API
* EventBridge scheduled execution
* DynamoDB persistence
* S3 uploads
* Secrets and environment configuration
* Terraform-managed infrastructure
* GitHub Actions automation

**Tech Stack:** AWS Lambda, API Gateway, EventBridge, DynamoDB, S3, Terraform, Python, GitHub Actions

---

### [Terraform Three-Tier AWS Infrastructure](https://github.com/Aboubakr2000Cloud/terraform-three-tier)

A modular and reproducible three-tier AWS architecture demonstrating infrastructure-as-code practices and Terraform state management.

**Architecture:**

* Network layer
* Compute layer
* Database layer
* Reusable Terraform modules
* Remote state in S3
* State locking
* GitHub Actions validation

**Tech Stack:** Terraform, AWS VPC, EC2, RDS, S3, DynamoDB, GitHub Actions

---

### [EC2-RDS Application](https://github.com/Aboubakr2000Cloud/EC2-RDS-App)

A production-style AWS application architecture combining load balancing, auto scaling, compute, and managed database services.

**Architecture:**

* Application Load Balancer
* Auto Scaling Group
* EC2
* RDS MySQL
* S3
* DynamoDB
* Security group isolation
* Multi-tier networking

**Tech Stack:** AWS EC2, ALB, ASG, RDS, S3, DynamoDB, VPC, Python, Bash

---

### [Backup Automation System](https://github.com/Aboubakr2000Cloud/backup-automation)

A production-oriented Python backup automation system designed around reliability, integrity, and lifecycle management.

**Capabilities:**

* Automated directory backups
* Archive and compression
* SHA-256 checksum generation and verification
* Backup integrity validation
* Intelligent retention and rotation
* S3 upload integration
* CLI-based operation
* Error handling and logging

**Tech Stack:** Python, Bash, tar/gzip, SHA-256, AWS S3, argparse, subprocess

---

## 🔄 ECS Platform Evolution

The ECS Weather Platform was deliberately developed through multiple engineering stages rather than as a collection of unrelated projects.

* **[ECS Weather Platform](https://github.com/Aboubakr2000Cloud/ecs-weather-platform)** — Initial containerized AWS deployment using ECS Fargate, ECR, Terraform, ALB, and RDS.
* **[ECS Weather Platform — CI/CD](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-cicd)** — Added automated testing, quality gates, Docker image builds, ECR publishing, and ECS deployment through GitHub Actions.
* **[ECS Weather Platform — Monitoring](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-with-monitoring)** — Added CloudWatch Container Insights, dashboards, alarms, and SNS notifications.
* **[ECS Weather Platform — Security Hardening](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-secured)** — Added KMS, IAM hardening, Secrets Manager, Parameter Store, CloudTrail, GuardDuty, and automated secret scanning.

The final secured repository represents the complete platform.

---

## 📚 Additional Projects

### Infrastructure & AWS

* **[ALB / ASG Deployer](https://github.com/Aboubakr2000Cloud/ALB-ASG-deployer)** — Highly available EC2 architecture using ALB, Auto Scaling Groups, multi-AZ networking, health checks, and automated scaling.
* **[VPC Infrastructure Deployer](https://github.com/Aboubakr2000Cloud/VPC-Infra-Deployer)** — AWS VPC infrastructure built from scratch using Bash and the AWS CLI.
* **[Cloud Nginx Deployer](https://github.com/Aboubakr2000Cloud/cloud-nginx-deployer)** — Automated EC2 deployment with user-data configuration, Nginx, EBS, and AMI snapshot workflows.
* **[Terraform AWS Infra](https://github.com/Aboubakr2000Cloud/terraform-aws-infra)** — Declarative AWS infrastructure managed entirely through Terraform.

### Containers & Applications

* **[Containerized Weather App](https://github.com/Aboubakr2000Cloud/containerized-weather-app)** — Flask/MySQL application containerized with Docker Compose.
* **[Weather API Fetcher](https://github.com/Aboubakr2000Cloud/weather-api-fetcher)** — Python API automation with authentication, retry logic, logging, and error handling.

### Foundations & Automation

* **[Cloud Engineering Foundations](https://github.com/Aboubakr2000Cloud/cloud-engineering-foundations)** — Linux administration, Bash scripting, networking, and Python automation fundamentals.

---

## 🛠️ Skills

### Linux & Systems

* Linux administration
* File operations and permissions
* Process management
* Bash scripting
* Cron automation
* Networking fundamentals
* IPs, DNS, ports, TCP/UDP

### Python & Automation

* Python application development
* File I/O and automation
* REST API integration
* JSON processing
* Error handling and logging
* Retry patterns
* CLI development with argparse
* Backup and integrity automation
* AWS SDK integration

### AWS

* IAM
* VPC
* EC2
* S3
* RDS
* ALB / ASG
* ECS / ECR
* Lambda
* API Gateway
* EventBridge
* DynamoDB
* SNS
* CloudFront
* CloudWatch
* CloudTrail
* GuardDuty
* KMS
* Secrets Manager
* Systems Manager
* Cost Explorer

### Infrastructure as Code

* Terraform
* Reusable modules
* Remote state
* State locking
* Environment-specific configuration
* Infrastructure validation

### Containers & CI/CD

* Docker
* Docker Compose
* Amazon ECR
* Amazon ECS Fargate
* GitHub Actions
* Automated testing
* Quality gates
* Security scanning
* Deployment automation
* Smoke testing

### Observability & Security

* CloudWatch dashboards
* CloudWatch alarms
* Container Insights
* SNS notifications
* CloudTrail auditing
* GuardDuty
* KMS encryption
* IAM least privilege
* Secrets Manager
* Secret scanning
* Application and infrastructure logging

---

## 🎯 Portfolio Focus

The projects demonstrate practical experience across several areas of cloud engineering:

**Infrastructure & Architecture**
AWS networking, compute, databases, load balancing, high availability, multi-tier architectures, and managed cloud services.

**Infrastructure as Code**
Modular Terraform, reusable infrastructure components, remote state, state locking, and environment-based deployments.

**Containers & Platform Engineering**
Docker, Amazon ECR, ECS Fargate, application load balancing, service deployment, and container operations.

**CI/CD & Automation**
GitHub Actions, automated testing, quality gates, security scanning, image publishing, deployment automation, and smoke testing.

**Serverless & Event-Driven Systems**
Lambda, API Gateway, EventBridge, DynamoDB, S3, SNS, scheduled processing, and event-driven workflows.

**Security Engineering**
IAM least privilege, KMS, Secrets Manager, Parameter Store, CloudTrail, GuardDuty, and automated secret scanning.

**Observability & Operations**
CloudWatch dashboards, alarms, Container Insights, SNS notifications, logging, anomaly detection, and operational validation.

**Python & Systems Automation**
API integrations, CLI tooling, backup automation, compression, checksums, retention policies, S3 synchronization, logging, and reliability-focused automation.

**Cloud Architecture**
Designing systems that combine managed AWS services, application workloads, data persistence, security controls, automation, and operational visibility.

---

## 🚀 Engineering Approach

Across the portfolio, the focus is not simply on deploying individual AWS services, but on understanding how they work together as reliable systems.

Projects emphasize:

* Reproducible infrastructure
* Automation over manual operations
* Least-privilege security
* Managed AWS services where appropriate
* Failure handling and troubleshooting
* Observability and operational visibility
* Automated validation
* Clear architectural boundaries
* Infrastructure and application separation
* Documentation of technical decisions

The portfolio reflects an engineering mindset centered on **building, deploying, debugging, securing, and operating cloud systems**.

---

## 🔗 Connect

* **GitHub:** [Aboubakr2000Cloud](https://github.com/Aboubakr2000Cloud)
* **Portfolio Index:** [cloud-portfolio-index](https://github.com/Aboubakr2000Cloud/cloud-portfolio-index)
* **LinkedIn:** [Aboubakr Ijannane](https://www.linkedin.com/in/aboubakr-ijannane-a0643b15b/)

