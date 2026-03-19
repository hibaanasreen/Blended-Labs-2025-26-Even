# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : HIBA NASREEN M

Reg no : 212224040117

Date : 19-03-2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Launch multiple servers.

2.Deploy the application on each server.

3.Create a load balancer.

4.Add servers to the load balancer.

5.Configure auto-scaling.

6.Test load distribution.
---

## Output Screenshots 

<img width="1919" height="971" alt="Screenshot 2026-03-12 211103" src="https://github.com/user-attachments/assets/8fa7df4a-3ee1-4074-a024-c10c1e0bce50" />

<img width="1919" height="903" alt="Screenshot 2026-03-12 211725" src="https://github.com/user-attachments/assets/586f6a3a-b2b7-4e9e-acfc-1022b58f12c8" />

<img width="1919" height="910" alt="Screenshot 2026-03-12 212615" src="https://github.com/user-attachments/assets/601f9ba0-ecea-476f-a486-3ec2fa5b918d" />

<img width="1919" height="905" alt="Screenshot 2026-03-12 214730" src="https://github.com/user-attachments/assets/e97c5e16-3960-4a8b-9cc4-8715d635a361" />

<img width="1912" height="900" alt="Screenshot 2026-03-12 215935" src="https://github.com/user-attachments/assets/0e1d0985-ca8e-435b-a5ad-dc52b372f2d0" />

<img width="1919" height="920" alt="Screenshot 2026-03-12 220136" src="https://github.com/user-attachments/assets/7f4f77ee-4ab2-4e57-83d5-f330444190ef" />

## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
