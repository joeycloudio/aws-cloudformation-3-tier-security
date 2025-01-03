# aws-cloudformation-3-tier-security

This CloudFormation template deploys a secure, 3-tier AWS architecture in us-east-1 with an emphasis on security best practices. 
It includes: 
- VPC, EC2 instances, ALB, and RDS for a web application.
- IAM roles, security groups, and logging configured for security and compliance.
- Designed with security, scalability, and fault tolerance in mind, though some features like Multi-AZ RDS or Auto Scaling are not included for demonstration purposes.
- Focused on providing a foundational AWS infrastructure for secure and resilient application deployment.

Some resources in this resume project are strictly for demonstration purposes. This template provides a foundational starting point however is not complete production-ready.

For example: there was no website name or ACM in place to fully accomodate true https requests from clients.
