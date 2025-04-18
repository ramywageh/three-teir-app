# Three-Tier DevSecOps Web Application on AWS EKS

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)

A production-ready implementation of a three-tier web application with full DevSecOps pipeline on AWS EKS.

## 📋 Overview

This project demonstrates:
- Infrastructure as Code (IaC) with Terraform
- CI/CD automation with Jenkins
- GitOps deployment using ArgoCD
- Security scanning with Trivy and SonarQube
- Monitoring with Prometheus and Grafana

## 🛠️ Architecture

![Architecture Diagram](docs/architecture.png) *(replace with your actual diagram)*

## ⚙️ Technologies Used

**Core Stack:**
- **AWS Services**: EKS, EC2, VPC, ECR, S3, DynamoDB
- **Orchestration**: Kubernetes, Helm
- **Automation**: Terraform, Jenkins, ArgoCD
- **Security**: Trivy, SonarQube, OWASP Dependency-Check
- **Monitoring**: Prometheus, Grafana

## 🚀 Deployment Steps

### Prerequisites
- AWS account with necessary permissions
- Terraform v1.0+
- AWS CLI configured
- kubectl and eksctl installed

### 1. Infrastructure Setup
```bash
cd terraform/
terraform init
terraform plan
terraform apply

### Key Features:
1. **Badges** - Visual tech stack indicators
2. **Clear Sections** - Easy navigation
3. **Code Blocks** - Ready-to-use commands
4. **Structure Visualization** - Quick understanding of repo layout
5. **Security Highlights** - DevSecOps emphasis
6. **Contributing Guide** - Encourages collaboration


