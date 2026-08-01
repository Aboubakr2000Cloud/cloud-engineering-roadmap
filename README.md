# Cloud Engineering Portfolio

## Overview

A collection of production-style cloud infrastructure and automation projects — covering Linux, Python, AWS, Terraform, Docker, and CI/CD. Each project below is a standalone, deployed, and documented system, built as part of an ongoing self-directed specialization in cloud infrastructure engineering.

---

## Featured Projects

### [ECS Weather Platform – Security Hardening](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-secured)
The security-hardened evolution of a full production-style AWS platform — containerized on ECS with complete CI/CD and CloudWatch monitoring, further secured with customer-managed KMS keys, IAM least-privilege policies, Secrets Manager, Parameter Store, CloudTrail auditing, and automated secret scanning (TruffleHog). Every hardening change was verified to preserve full application availability and database connectivity.

**Tech Stack:** Terraform, AWS KMS, IAM, Secrets Manager, Systems Manager, CloudTrail, ECS, Docker, GitHub Actions, CloudWatch

*Built in stages — see the full progression: [initial platform](https://github.com/Aboubakr2000Cloud/ecs-weather-platform) → [CI/CD added](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-cicd) → [monitoring added](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-with-monitoring) → security hardening (this repo).*

---

### [Terraform Three-Tier AWS Infrastructure](https://github.com/Aboubakr2000Cloud/terraform-three-tier)
Modularized, fully reproducible three-tier AWS architecture (network, compute, data layers) deployed via Terraform, with remote state management.    

**Tech Stack:** Terraform, AWS VPC/EC2/RDS, S3 backend, DynamoDB state locking

---

### [EC2-RDS Application](https://github.com/Aboubakr2000Cloud/EC2-RDS-App)
Application deployment extending a load-balanced, auto-scaling EC2 environment with a managed RDS database backend, using security group isolation between the application and data tiers.   

**Tech Stack:** AWS EC2, RDS, security groups, networking

---

### [ALB / ASG Deployer](https://github.com/Aboubakr2000Cloud/ALB-ASG-déployer)
Highly available, auto-scaling EC2 environment behind an Application Load Balancer, scaling automatically based on CPU load.


**Tech Stack:** AWS ALB, Auto Scaling Groups, EC2, CloudWatch

---

### [Backup Automation System](https://github.com/Aboubakr2000Cloud/backup-automation)
Production-grade backup tool with compression, SHA-256 checksum validation, intelligent rotation, and S3 upload integration.


**Tech Stack:** Python, subprocess, tar/gzip, checksums, CLI development

---

### [Weather API Fetcher](https://github.com/Aboubakr2000Cloud/weather-api-fetcher)
Python automation tool with intelligent retry logic, API authentication, and production-ready error handling.   

**Tech Stack:** Python, requests, logging, argparse, environment variables

---

## Additional Projects
- **[ECS Weather Platform](https://github.com/Aboubakr2000Cloud/ecs-weather-platform)** — Initial containerized deployment stage of the weather platform on AWS ECS
- **[ECS Weather Platform — CI/CD](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-cicd)** — Added a full CI/CD pipeline via GitHub Actions to the ECS deployment
- **[ECS Weather Platform — Monitoring](https://github.com/Aboubakr2000Cloud/ecs-weather-platform-with-monitoring)** — Added CloudWatch monitoring and alerting to the CI/CD-enabled platform
- **[Weather Serverless Platform](https://github.com/Aboubakr2000Cloud/weather-serverless-platform)** — Event-driven serverless pipeline using Lambda, API Gateway, and SNS notifications
- **[VPC Infrastructure Deployer](https://github.com/Aboubakr2000Cloud/VPC-Infra-Deployer)** — Production-structured AWS VPC built from scratch via Bash and the AWS CLI
- **[Cloud Nginx Deployer](https://github.com/Aboubakr2000Cloud/cloud-nginx-deployer)** — End-to-end EC2 deployment with user-data automation, EBS, and AMI snapshotting
- **[Terraform AWS Infra](https://github.com/Aboubakr2000Cloud/terraform-aws-infra)** — Additional Terraform-managed AWS infrastructure
- **[Containerized Weather App](https://github.com/Aboubakr2000Cloud/containerized-weather-app)** — Docker-containerized version of the weather platform
- **[Foundational projects: Linux, Bash & Python Automation](https://github.com/Aboubakr2000Cloud/cloud-engineering-foundations)** — Early-stage work covering Linux administration, Bash scripting, and Python automation fundamentals

---

## Skills

### Linux & Systems  
- File operations & permissions, process management, Bash scripting, cron automation, core networking (IPs, DNS, ports, TCP/UDP)

### Python Development  
- Core language & data structures, file I/O, API integration & JSON handling, error handling/logging/retry patterns, CLI tooling with argparse

### AWS  
- IAM, S3, EC2, VPC, RDS, ALB/ASG, ECS, Lambda (in progress), CloudWatch, IAM (least privilege), KMS, AWS Secrets Manager, Parameter Store, Serverless architectures (Lambda, API Gateway)

### Infrastructure as Code  
- Terraform (modules, remote state, workspaces)

### Containers & CI/CD  
- Docker, Docker Compose, AWS ECS/ECR, GitHub Actions, CI/CD pipeline design

### In Progress  
- A capstone project integrating full-stack cloud architecture with monitoring and IaC.

---

## Connect
- GitHub: [Aboubakr2000Cloud](https://github.com/Aboubakr2000Cloud)
- LinkedIn: [https://www.linkedin.com/in/aboubakr-ijannane-a0643b15b/]
