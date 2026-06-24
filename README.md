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
- Application Load Balancer (ALB) – Distributes incoming traffic across multiple EC2 instances
- Target Group – Routes traffic from ALB to healthy EC2 instances
- Auto Scaling Group (ASG) – Automatically adds or removes EC2 instances based on demand
- EC2 Instances (Amazon Linux) – Hosts the application workload
- CloudWatch Monitoring – Monitors CPU utilization and triggers scaling policies.

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

## Screenshots of Test
*  EC2 Instances
- [EC2](screenshots/ec2.png)

*  Load Balancer
- [ALB](screenshots/alb.png)

*  Target Group
- [Target Group](screenshots/target-group.png)

*  Auto Scaling Group
- [ASG](screenshots/asg.png)

*  CloudWatch Metrics
- [CloudWatch](screenshots/cloudwatch.png)

*  Application Output
- [ALB DNS](screenshots/alb-dns.png)      
                  ################################                               ##############################
