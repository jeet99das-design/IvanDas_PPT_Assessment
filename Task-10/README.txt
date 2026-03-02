==============================
Task 10: VPC 3-Tier Architecture
==============================

Objective:
To design and implement a secure 3-tier architecture in AWS with public and private subnets.

Architecture Components:
- VPC with custom CIDR block
- 1 Public Subnets 
- 1 Private Subnets 
- Internet Gateway (IGW)
- NAT Gateway
- Route Tables
- Security Groups and NACLs
- Bastion Host for SSH access

Implementation Steps:
1. Created a custom VPC.
2. Created public and private subnets in different Availability Zones.
3. Attached Internet Gateway to VPC.
4. Created NAT Gateway in public subnet.
5. Configured route tables:
   - Public route table → IGW
   - Private route table → NAT Gateway
6. Launched EC2 instance in public subnet (Bastion Host).
7. Launched EC2 instance in private subnet.
8. Configured SSH tunneling from Bastion to private instance.

Outcome:
Successfully deployed a secure 3-tier architecture with controlled access to private resources.

