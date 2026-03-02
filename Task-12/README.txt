==============================
Task 12: Website Down Alert using Lambda (Canary) + SNS
==============================

Objective:
To monitor website uptime and receive alerts if the website goes down.

Services Used:
- CloudWatch Synthetics Canary
- AWS Lambda
- Amazon SNS
- CloudWatch Alarms

Implementation Steps:
1. Created a Canary to monitor website URL.
2. Configured CloudWatch alarm for failure condition.
3. Created SNS topic and email subscription.
4. Linked CloudWatch alarm to SNS notification.

Outcome:
System successfully sends email alerts when the monitored website becomes unavailable.

