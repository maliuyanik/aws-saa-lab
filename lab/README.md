# Lab: production-style web application on AWS

Goal: build a typical production web application setup on AWS with Terraform: a load balancer with TLS, servers and a database in private subnets, and monitoring.

## Before the first lab

- [ ] AWS Budgets alarm set up (monthly limit 5-10 USD)
- [ ] Root account MFA enabled, daily work done with an IAM user
- [ ] Everything created with Terraform, removed with terraform destroy after each session

## Components

- Network: VPC with public and private subnets
- Compute: EC2 in a private subnet
- Traffic and TLS: Application Load Balancer with an ACM certificate
- Database: RDS for PostgreSQL
- Monitoring: CloudWatch alarms
- Access: IAM roles and policies
- Deployment: CI/CD pipeline, to be decided

## Steps

- [ ] 1. VPC with public and private subnets
- [ ] 2. EC2 instance in a private subnet
- [ ] 3. Application Load Balancer with an ACM certificate
- [ ] 4. RDS PostgreSQL in a private subnet
- [ ] 5. CloudWatch alarms
- [ ] 6. Architecture diagram (Mermaid) in this file
- [ ] 7. Write down the main decisions and why I made them

Terraform code goes in [terraform/](terraform/).
