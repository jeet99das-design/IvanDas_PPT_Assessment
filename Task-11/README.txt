==============================
Task 11: S3 Upload Email Notification (Lambda + SNS)
==============================

Objective:
To trigger an email notification whenever a file is uploaded to an S3 bucket.

Services Used:
- Amazon S3
- AWS Lambda
- Amazon SNS

Implementation Steps:
1. Created an S3 bucket.
2. Created SNS topic and subscribed email endpoint.
3. Created Lambda function with required IAM role.
4. Configured S3 event trigger for object upload.
5. Connected Lambda to SNS to publish notification.

Outcome:
Email notification successfully received whenever a new object was uploaded to the S3 bucket.

