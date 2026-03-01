# Task 7 – Create EFS and Connect to Multiple Ubuntu Instances

# Objective
To create a shared file system using Amazon EFS and mount it on multiple EC2 instances.

# Services Used
- Amazon EC2
- Amazon EFS

# Implementation Steps

1. Launched two EC2 instances (Ubuntu and Amazon LINUX).
2. Created EFS file system.
3. Configured a new Security Group to allow NFS.
4. Installed NFS client and EFS mount helper on both EC2 instances.
6. Created test file on Instance 1.
7. Verified file visibility on Instance 2.

# Key Learning

EFS provides scalable shared storage accessible by multiple EC2 instances simultaneously.

# Proof

Screenshots attached showing:
- EFS creation
- Shared file visible on both instances