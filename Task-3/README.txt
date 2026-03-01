# Task 3 – Attach EBS Volume from Different AZ using Snapshot

# Objective
To demonstrate cross-Availability Zone volume attachment using EBS Snapshot.

# Services Used
- Amazon EC2
- Amazon EBS
- EBS Snapshot

# Implementation Steps

1. Launched EC2 instance in AZ-A.
2. Created EBS volume in same AZ and attached to EC2.
3. Created snapshot of the attached volume.
4. Created new EBS volume from snapshot in AZ-C.
5. Launched new EC2 instance in AZ-C.
6. Attached newly created volume to EC2 in AZ-C.
7. Verified attachment using 'lsblk'.

# Key Learning

EBS volumes are AZ-specific and cannot be directly attached across AZs.  
Snapshots allow volume recreation in different Availability Zones.

# Proof

Screenshots included:
- Volume attached in AZ-A
- Snapshot created successfully
- Volume attached in AZ-C