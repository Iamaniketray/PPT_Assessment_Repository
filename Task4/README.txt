# Task 4: ASG and ELB in EC2

Objective:
To configure Auto Scaling Group with Application Load Balancer to achieve high availability.

Services Used:
- Amazon EC2
- Launch Template
- Auto Scaling Group
- Application Load Balancer
- Target Group

Architecture:
User → Load Balancer → EC2 Instances (Managed by ASG)

Result:
Traffic is distributed across multiple EC2 instances.
If one instance fails, ASG automatically replaces it.
System remains highly available.