🌐 AWS Scalable & Secure Web Application Deployment
This project showcases a complete AWS-based cloud infrastructure for hosting a highly available, secure, and scalable PHP-based dynamic web application. Designed as part of a real-world scenario, it simulates responsibilities expected from a Cloud Architect, ensuring best practices in network isolation, database management, auto-scaling, disaster recovery, and global content delivery.

📌 Key Features
Isolated Network Environment using Amazon VPC with security groups and NACLs.

Managed Database with Amazon RDS (Multi-AZ) for automated backups, patching, and failover.

Disaster Recovery with EC2 and RDS backups using AWS Backup.

Auto-Scaling EC2 Instances: Maintain 2 minimum, scale up to 4 during high traffic.

High Availability via Application Load Balancer (ALB) and health checks.

Global Caching through Amazon CloudFront CDN for low-latency access worldwide.

Automated Monitoring & Incident Alerts via CloudWatch, Lambda, and Amazon SES.

Dynamic PHP Web Application connected to the RDS backend to store user input.

🛠️ Tech Stack & AWS Services
Frontend & Backend: PHP

Compute: Amazon EC2 (with Auto Scaling Group)

Database: Amazon RDS (MySQL/PostgreSQL - Multi-AZ)

Networking: Amazon VPC, Security Groups, NACLs

Load Balancing: Application Load Balancer (ALB)

Backup & DR: AWS Backup, RDS Snapshots

Monitoring: Amazon CloudWatch, Lambda, SES

Global Delivery: Amazon CloudFront

📄 Use Case
This project is ideal for demonstrating skills in:

Cloud Infrastructure Design

High Availability Architecture

AWS Automation & Monitoring

Secure and Scalable Web Deployment

