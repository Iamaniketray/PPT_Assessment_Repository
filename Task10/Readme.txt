# Task 10: VPC 3-Tier Architecture

Objective:
To design a secure 3-tier VPC architecture using public and private subnets.

Services Used:
- Amazon VPC
- Amazon EC2
- NAT Gateway
- Internet Gateway
- Route Tables
- Security Groups

Architecture:
Internet → IGW → Public Subnet → NAT → Private App → Private DB

Steps Performed:
1. Created custom VPC
2. Created public and private subnets
3. Attached Internet Gateway
4. Configured NAT Gateway
5. Launched EC2 instances in each tier
6. Configured security groups
7. Verified SSH tunneling via bastion host

Result:
Successfully implemented a secure 3-tier architecture with proper network isolation.