# S3 Access via IAM Role

## Project Overview
This project demonstrates securely accessing an Amazon S3 bucket from an Ubuntu EC2 instance using IAM roles, eliminating the need for access keys.

## Objective
- Attach an IAM role with proper S3 permissions to an EC2 instance.
- Access and manage S3 objects securely from Ubuntu.
- Understand role-based access management in AWS.

## Steps
1. Create an **IAM Role** with S3 access permissions.
2. Attach the IAM role to the target EC2 instance.
3. SSH into the EC2 instance and test access:
   ```bash
   aws s3 ls s3://<bucket-name>/
   aws s3 cp testfile.txt s3://<bucket-name>/