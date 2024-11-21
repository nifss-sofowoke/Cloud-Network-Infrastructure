# About This Project
My purpose for this project was to learn IaC using AWS CloudFormation, and I challenged myself to build and deploy a Network Cloud infrastructure. 
Basically, this is my first IaC project.

## AWS CloudFormation Template
The CF template in this repo was designed to create and deploy an automated and scalable network cloud architecture that:

- consists of 3 public subnets
- hosts an autoscaling group with a minimum of two and a maximum of five EC2 instances to guarantee high availability and fault tolerance
- configures the ASG to scale out when the average CPU utilization of the web servers increases to 50%

# Infrastructure Diagram
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*a3lCoreZb-p4t5WvA6hvFA.jpeg">

# Project Link
https://medium.com/aws-in-plain-english/building-a-highly-available-network-cloud-infrastructure-with-aws-cloudformation-4feedb5ff16c
