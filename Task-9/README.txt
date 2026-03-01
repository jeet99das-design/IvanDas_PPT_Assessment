# Task 9 – Access S3 from EC2 using IAM Role

# Objective
To securely access S3 from EC2 using IAM Role instead of access keys.

# Services Used
- Amazon EC2
- Amazon S3
- IAM Role

# Implementation Steps

1. Created IAM Role for EC2.
2. Attached AmazonS3FullAccess policy to the role.
3. Attached role to EC2 instance.
4. Installed AWS CLI.
5. Verified S3 access using 'aws s3 ls' command.

# Key Learning

IAM Roles provide secure temporary credentials to EC2 instances, eliminating the need to store access keys.

# Proof

Screenshots attached showing:
- IAM Role configuration
- Successful S3 access from EC2 terminal