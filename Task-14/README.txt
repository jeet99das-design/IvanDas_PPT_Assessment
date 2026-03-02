==============================
Task 14: CloudWatch Alarm (70% CPU → Auto Stop + Email)
==============================

Objective:
To automatically stop EC2 instance and send email alert when CPU usage exceeds 70%.

Services Used:
- Amazon CloudWatch
- Amazon EC2
- Amazon SNS

Implementation Steps:
1. Created CloudWatch alarm for CPU Utilization > 70%.
2. Configured alarm action to stop EC2 instance.
3. Created SNS topic and email subscription.
4. Linked alarm to SNS notification.

Outcome:
EC2 instance automatically stops and sends email notification when CPU threshold is exceeded.

