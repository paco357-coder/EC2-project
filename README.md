## Terraform (Infrastructure as Code)

This project includes a Terraform configuration to provision an AWS EC2 instance using Infrastructure as Code (IaC).

### Terraform Overview
- Provider: AWS
- Region: us-east-1
- Resource: EC2 instance
- Instance type: t2.micro (Free Tier eligible)
- AMI: Amazon Linux 2023

### Terraform Files
- `terraform/main.tf` – Defines the AWS provider and EC2 instance resource

### Purpose
The Terraform configuration is included to demonstrate:
- Infrastructure as Code principles
- Automated cloud resource provisioning
- Real-world AWS + Terraform experience

⚠️ Note: Terraform code is provided for demonstration purposes and was not applied to avoid unnecessary AWS charges.
