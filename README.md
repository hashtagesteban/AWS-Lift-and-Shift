# AWS-Lift-and-Shift
Shift on prem to AWS using EC2


AWS Services: EC2, S3, Route 53, ACM, ELB, ASG

Open Source Software:  Apache Tomcat, MYSQL, Memcached, RabbitMQ

Other tools: Maven


Java Application: Vprofile app


<a href="https://github.com/hashtagesteban/vprofile-project"> Source Code</a>

![Architecture](https://github.com/hashtagesteban/AWS-Lift-and-Shift/assets/114188090/eab1d11d-f3ec-440a-8510-d8b1d840099d)

## Problem
Complex management
Manual process
Difficult to automate
Time consuming



## Solution
IAAS
ELB -> ASG -> EC2 




## Objectives
Create:
  Key pairs
  Security Groups![Security Groups](https://github.com/hashtagesteban/AWS-Lift-and-Shift/assets/114188090/421b0b5f-1b0a-4eca-822a-46096be66814)



Launch EC2 instances


![EC2 instances](https://github.com/hashtagesteban/AWS-Lift-and-Shift/assets/114188090/7295d23b-e8c2-4329-862a-0f04559a5c6f)

Update ip mapping in R53

Build aplication from source code locally

Upload artifact to S3

Download artifact onto Tomcat instances

Create AMI of Tomcat instances

Set up Autoscaling groups

Set up ELB with certificate

Map ELB to our domain name




















