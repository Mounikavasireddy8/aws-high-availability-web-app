# AWS-High-Availability-Web-App
Highly available web application using EC2, ALB, and Auto Scaling
# Highly Available Web Application on AWS

## Description
This project demonstrates how to build a highly available and scalable web application on AWS using EC2, Application Load Balancer, and Auto Scaling Group.

## Architecture
- EC2 instances deployed across multiple Availability Zones
- Application Load Balancer for traffic distribution
- Auto Scaling Group for fault tolerance and scaling
- CloudWatch for monitoring and scaling metrics

## Traffic Flow
User → Application Load Balancer → EC2 instances (Multi-AZ)

## Why This Architecture
- Ensures high availability
- Handles traffic spikes automatically
- Avoids single point of failure.
