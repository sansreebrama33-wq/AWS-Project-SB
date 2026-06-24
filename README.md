## AWS Project
Highly Available and Scalable Web Application Deployment on AWS using EC2,ASG,ALB.

## Overview
This project demonstrates a highly available and scalable web application architecture built on AWS using core cloud services. The system dynamically 
scales compute resources using an Auto Scaling Group (ASG) and automatically handles traffic load using an Application Load Balancer (ALB).
      It ensures:
               - High availability 
               - Fault Tolerance
               - Automatic Scaling based on demand
               - Efficient traffic distribution across multiple EC2 instances.

## Architecture
- EC2 Instances (Amazon Linux)
- Auto Scaling Group (ASG)
- Application Load Balancer (ALB)
- Target Group
- CloudWatch Monitoring (CPU Metrics)

## AWS Service used
- Amazon EC2
- VPC
- Security Group
- Launch Template
- Auto Scaling Group
- Application Load Balancer
- Amazon CloudWatch

## Key Features
- Automatically distributes traffic using ALB
- Scales EC2 instances based on CPU utilization
- Maintains application availability during traffic spikes
- Self-healing infrastructure (replaces unhealthy instances)
- Monitored using CloudWatch metrics.

## Steps Implementation 
- Launch Template Creation
- Create Target Group
- Configure Application Load Balancer
- Setup Auto Scaling Group
- Testing the Setup

                        ################################                               ##############################
