🏗️ Two-Tier AWS Infrastructure with Terraform 

![AWS Infrastructure Diagram](https://github.com/fareedmohamed11/Two-Tier-AWS-Infrastructure-with-Terraform/blob/55d3e1fce84631ccc7a94cffb0b8d421e32a5546/68747470733a2f2f696d6775722e636f6d2f583464474267362e676966.gif)

## 📌 Overview

This project demonstrates a **Two-Tier architecture on AWS** using **Terraform** for Infrastructure as Code (IaC).  
It follows a modular and security-enhanced approach to create a **scalable**, **secure**, and **maintainable** infrastructure.

---

## ✅ Key Features

- **Modular Architecture** – Reusable Terraform modules for better management
- **Infrastructure as Code (IaC)** – Automate AWS resource provisioning
- **Security Best Practices** – IAM roles, policies, and WAF integration
- **Scalability & High Availability** – Auto Scaling, Load Balancing, and Route 53
- **Database Integration** – Managed Amazon RDS deployment
- **SSL & CDN Optimization** – Secure connections and content acceleration

 ## 📖 Step-by-Step Guide
 📌 Read the full tutorial with screenshots:
 https://blog.prodevopsguy.xyz/deploy-two-tier-architecture-on-aws-using-terraform 
---

## 🚀 Getting Started

### 🔗 **1 Clone the Repository** 
 https://github.com/fareedmohamed11
 cd DevOps-Projects/DevOps-Project-11/

### 🧱 **2 Initialize and Apply Terraform**
terraform init
terraform plan -var-file=variables.tfvars
terraform apply -var-file=variables.tfvars --auto-approve

### 🧹 **3 Cleanup (Destroy Infrastructure**
terraform destroy -var-file=variables.tfvars --auto-approve

# Project Architecture Highlights

## Networking & Security
- **VPC & Subnets**: Isolated environment for your application.
- **IAM & Role-Based Access Control**: Fine-grained security permissions.
- **AWS WAF**: Protect against common web threats.

## Compute & Scaling
- **Auto Scaling Group**: Dynamic scaling based on demand.
- **Elastic Load Balancer (ALB)**: Efficient traffic distribution.
- **EC2 Instances**: Reliable compute capacity.

## Storage & Database
- **Amazon RDS**: Managed database for scalability and reliability.
- **S3 Buckets**: Secure storage for application assets.

## Networking & Optimization
- **Amazon Route 53**: Scalable domain name system (DNS).
- **Amazon CloudFront (CDN)**: Faster content delivery worldwide.
- **SSL/TLS Encryption**: Secure communication with ACM.









