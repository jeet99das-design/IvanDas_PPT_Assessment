# Task 4 – Auto Scaling Group and Load Balancer

# Objective
To implement high availability and auto scaling using ASG and Application Load Balancer.

# Services Used
- Amazon EC2
- Auto Scaling Group
- Application Load Balancer
- Target Group

# Implementation Steps

1. Created EC2 instance and installed Nginx.
2. Created AMI from configured instance.
3. Created Target Group.
4. Created Application Load Balancer.
5. Created Launch Template using AMI.
6. Created Auto Scaling Group with:
   - Minimum: 2
   - Desired: 2
   - Maximum: 5
7. Attached ASG to Load Balancer.
8. Verified website using Load Balancer DNS.

# Key Learning

Auto Scaling Group automatically maintains instance count.  
Load Balancer distributes traffic across multiple instances.

# Proof

Screenshots attached showing:
- ASG running instances
- Load Balancer configuration
- Website accessed via Load Balancer DNS