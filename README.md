# Terraform Secure Infrastructure on AWS

This project provisions secure AWS infrastructure using Terraform.

## Features
- VPC with public/private subnets
- EC2 instance in private subnet
- Security groups with restricted access
- Modular Terraform structure
- IAM configuration

## Structure
- modules/network
- modules/ec2
- iam.tf
- providers.tf

## Usage
```bash
terraform init
terraform plan
terraform apply