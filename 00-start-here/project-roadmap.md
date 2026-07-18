# AWS Project Roadmap

This file tracks AWS project ideas for my **AWS Cloud Journey 2026**.

The project roadmap is **not limited to 30 days**.

It includes:

* beginner-friendly AWS projects
* multi-AWS-service projects
* real-world AWS builds
* portfolio projects
* my Java, Spring Boot, full-stack, and AI projects adapted for AWS

Some project ideas are inspired by public AWS portfolio-style learning repositories, but each project will be implemented, documented, cost-checked, cleaned up, and explained in my own way.

---

## Project Roadmap Principle

The goal is not to build many AWS projects quickly.

The goal is to build useful projects that show:

* AWS fundamentals
* security awareness
* cost awareness
* troubleshooting ability
* cleanup discipline
* architecture thinking
* interview-ready explanation
* Java/backend/cloud connection

---

## Cost-Safe Project Mindset

This project roadmap is **not a command to build everything immediately**.

Every project is optional until I understand:

1. Why I am creating it
2. What it may cost
3. How it is billed
4. How to monitor it
5. How to clean it up
6. Whether a cheaper or smaller version is enough

Simple rule:

```text
Understand cost before creating.
Build the smallest version first.
Monitor while testing.
Clean up after practice.
Document what was kept.
```

---

## Project Status Meaning

| Status             | Meaning                                           |
| ------------------ | ------------------------------------------------- |
| Planned            | Project idea saved, not started yet               |
| Cost Review Needed | Project should not start until pricing is checked |
| Safe to Start      | Cost and cleanup steps are understood             |
| In Progress        | Project is being built                            |
| Completed          | Project is built and documented                   |
| Cleaned Up         | Resources were deleted after practice             |
| Kept Intentionally | Resources are kept with reason documented         |
| Future             | Saved for later                                   |

---

## Cost Risk Labels

| Cost Risk          | Meaning                                                      |
| ------------------ | ------------------------------------------------------------ |
| Low Cost           | Usually safe for beginner learning if used carefully         |
| Medium Cost        | Needs pricing check, budget alert, and cleanup plan          |
| High Cost          | Do not start without detailed cost estimate and cleanup plan |
| Cost Review Needed | Pricing must be checked before starting                      |
| Planning Only      | No AWS resource creation yet                                 |

---

# 01 Beginner-Friendly Projects

These projects are simple first AWS projects. They focus on safety, basic AWS services, and small hands-on tasks.

Folder:

```text
02-mini-projects/01-beginner-friendly-projects/
```

| My Project Name                       | AWS Services                   | Related Day(s) | Reference Hint                                                   | Cost Risk            | Status             |
| ------------------------------------- | ------------------------------ | -------------- | ---------------------------------------------------------------- | -------------------- | ------------------ |
| Billing Alerts Setup                  | AWS Budgets, Billing Dashboard | Day 02         | Level 100 - Create Three Billing Alarms / Create a Cost Budget   | Low Cost             | Planned          |
| Monthly Cost Budget Setup             | AWS Budgets                    | Day 02         | Level 100 - Create a Cost Budget                                 | Low Cost             | Planned          |
| IAM User and Group Setup              | IAM                            | Day 04         | Level 100 - Create an IAM User                                   | Low Cost             | Planned            |
| IAM Read-Only Access Setup            | IAM                            | Day 05         | IAM least privilege practice                                     | Low Cost             | Planned            |
| AWS CLI + S3 Bucket Setup             | AWS CLI, S3                    | Day 06         | Level 100 - Install & Configure AWS CLI then Create an S3 Bucket | Low Cost             | Planned            |
| Hello World Website on EC2            | EC2                            | Day 08         | Level 100 - Launch a Hello World Website on the Internet         | Medium Cost          | Cost Review Needed |
| Docker Image Push to ECR              | ECR, Docker, AWS CLI           | Day 10         | Level 100 - Push a Docker Image to Amazon ECR Repository         | Low / Medium Cost    | Planned            |
| RDS SQL Server Basics                 | RDS SQL Server                 | Day 11         | Level 100 - Creating an Amazon RDS DB Instance                   | High Cost            | Future             |
| DynamoDB Basic Table                  | DynamoDB                       | Day 12         | Level 100 - Create a DynamoDB Table                              | Low Cost             | Planned            |
| S3 Object Storage Basics              | S3                             | Day 13         | Level 100 - Create an S3 Bucket and Store an Object              | Low Cost             | Planned            |
| SNS Email Notification Demo           | SNS                            | Day 14         | Level 100 - Introduction to SNS                                  | Low Cost             | Planned            |
| Lambda Add Two Numbers                | Lambda, CloudWatch             | Day 15         | Level 100 - Create a Lambda Function to Add Two Numbers          | Low Cost             | Planned            |
| Static Webpage with S3 and CloudFront | S3, CloudFront                 | Day 16         | Level 100 - Host a Simple Static Webpage with S3 and CloudFront  | Low / Medium Cost    | Planned            |
| AWS Config Managed Rule Demo          | AWS Config                     | Day 17         | Level 100 - Use a Managed Config Rule                            | Medium Cost          | Cost Review Needed |
| CloudFormation Console Deployment     | CloudFormation, S3, DynamoDB   | Day 18         | Level 100 - Deploy a CloudFormation Template from AWS Console    | Depends on resources | Planned            |

---

# 02 Multi-AWS-Service Projects

These projects combine more than one AWS service and help build AWS integration thinking.

Folder:

```text
02-mini-projects/02-multi-aws-service-projects/
```

| My Project Name                  | AWS Services                       | Related Day(s) | Reference Hint                                                 | Cost Risk          | Status             |
| -------------------------------- | ---------------------------------- | -------------- | -------------------------------------------------------------- | ------------------ | ------------------ |
| Auto Scaling Group Demo          | EC2 Auto Scaling, CloudWatch       | Day 20         | Level 200 - Create an Auto Scaling Group                       | Medium Cost        | Cost Review Needed |
| Fargate Container Deployment     | ECS, Fargate, Docker               | Day 21         | Level 200 - Deploy a Docker Container Image on AWS Fargate     | Medium Cost        | Future             |
| Aurora MySQL Database Setup      | Aurora, RDS, VPC, Security Groups  | Day 22         | Level 200 - Create an Aurora RDS Database                      | High Cost          | Future             |
| Step Functions Two-Step Workflow | Lambda, Step Functions, CloudWatch | Day 23         | Level 200 - Setup a Simple State Machine with at least 2 Steps | Low / Medium Cost  | Planned            |
| Serverless API with API Gateway  | Lambda, API Gateway, IAM, Postman  | Day 24         | Level 200 - Create a Serverless API                            | Low / Medium Cost  | Planned            |
| CloudWatch Alarm Demo            | EC2 or Lambda, CloudWatch, IAM     | Day 25         | Level 200 - Create a CloudWatch Alarm                          | Low / Medium Cost  | Planned            |
| KMS Encrypted S3 Object          | KMS, S3, IAM                       | Day 26         | Level 200 - Create a new CMK in KMS and encrypt an object      | Medium Cost        | Future             |
| EFS Shared File System           | EFS, EC2                           | Day 27         | Level 200 - Create an EFS Shared File System                   | Medium / High Cost | Future             |

---

# 03 Real-World Projects

These projects are closer to real AWS infrastructure and should only be attempted after checking pricing carefully.

Folder:

```text
02-mini-projects/03-real-world-projects/
```

| My Project Name                          | AWS Services                              | Related Day(s)  | Reference Hint                                         | Cost Risk                        | Status |
| ---------------------------------------- | ----------------------------------------- | --------------- | ------------------------------------------------------ | -------------------------------- | ------ |
| SQL Server Backup and Restore on RDS     | RDS, S3                                   | Day 29          | Level 300 - SQLServer Native Backup and Restore on RDS | High Cost                        | Future |
| Terraform VPC Deployment                 | VPC, EC2, NAT Gateway, Terraform          | Day 30 - Day 32 | Level 300 - Deploy a VPC with Terraform                | High Cost if NAT Gateway is used | Future |
| Real-World Infrastructure Cleanup Review | Billing, Cost Explorer, cleanup checklist | Day 33          | Infrastructure review                                  | Planning Only                    | Future |

---

# 04 Portfolio Projects

These are larger projects suitable for GitHub, CV, LinkedIn, and interview discussion.

Folder:

```text
02-mini-projects/04-portfolio-projects/
```

| My Project Name                       | AWS Services                                                                                                                        | Related Day(s)  | Reference Hint                                                                               | Cost Risk          | Status |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | --------------- | -------------------------------------------------------------------------------------------- | ------------------ | ------ |
| Docker Swarm Cluster on EC2           | EC2, Docker Swarm, Nginx                                                                                                            | Day 34          | Level 400 - Create a Cluster of Virtual Machines Using Docker Swarm                          | Medium / High Cost | Future |
| Basic Web App with Amplify            | Amplify, AppSync, Lambda, DynamoDB                                                                                                  | Day 35 - Day 36 | Level 400 - Build a Basic Web Application                                                    | Cost Review Needed | Future |
| Bedrock Recipe Generator              | Amplify, Cognito, AppSync, Lambda, Bedrock                                                                                          | Day 37          | Level 400 - Build a Serverless Recipe Generator with AWS Amplify and Amazon Bedrock          | Cost Review Needed | Future |
| GenAI Apps with PartyRock and Bedrock | PartyRock, Bedrock, Amazon Q                                                                                                        | Day 38          | Level 400 - Building with Generative AI on AWS using PartyRock, Amazon Bedrock, and Amazon Q | Cost Review Needed | Future |
| Multi-Tier Highly Available Web App   | VPC, EC2, Aurora, S3                                                                                                                | Day 39          | Level 400 - Multi-Tier, Highly Available, Fault-Tolerant Web Application                     | High Cost          | Future |
| Highly Available WordPress App        | VPC, RDS, EFS, EC2, Auto Scaling, ALB                                                                                               | Day 40          | Level 400 - Building a Highly Available WordPress Web Application                            | High Cost          | Future |
| Continuous Delivery Pipeline          | CodePipeline, CodeBuild, Elastic Beanstalk, EC2 Auto Scaling                                                                        | Day 41 - Day 42 | Level 400 - Create a Continuous Delivery Pipeline                                            | Medium / High Cost | Future |
| Web App on EKS                        | Cloud9, ECR, EKS, Fargate                                                                                                           | Day 43          | Level 400 - Building Web Applications based on Amazon EKS                                    | High Cost          | Future |
| Large-Scale Data Processing Workflow  | Step Functions, S3, IAM, CloudWatch, X-Ray                                                                                          | Day 44          | Level 400 - Large-scale Data Processing with Step Functions                                  | Cost Review Needed | Future |
| SageMaker Fraud Detection Solution    | SageMaker, Lambda, S3, IAM, EC2, VPC, CloudWatch, SQS, Secrets Manager, CloudTrail, Route 53, SSM, API Gateway, SNS, CloudFormation | Day 45          | Level 400 - Complete ML Fraud Detection Solution using SageMaker                             | High Cost          | Future |
| Serverless Data Processing on AWS     | Lambda, Kinesis, DynamoDB, S3, Athena, Cognito                                                                                      | Day 46          | Level 400 - Serverless Data Processing on AWS                                                | Cost Review Needed | Future |
| AWS Cloud Resume Challenge            | S3, Lambda, DynamoDB, CloudFormation, Route 53, ACM, API Gateway, CloudFront                                                        | Day 47          | Level 400 - AWS Cloud Resume Challenge                                                       | Medium Cost        | Future |
| IoT and AI Video Monitoring System    | IoT Core, Rekognition, Lambda, CloudWatch, IoT Greengrass, S3                                                                       | Day 48          | Level 400 - Automated Video Monitoring with AWS IoT and AI/ML                                | Cost Review Needed | Future |
| Advanced Portfolio Review             | GitHub, README, screenshots, cost review                                                                                            | Day 49          | Advanced project summary                                                                     | Planning Only      | Future |

---

# 05 Java AWS Projects

These projects connect AWS learning with my Java backend, Spring Boot, full-stack, and AI project background.

Folder:

```text
02-mini-projects/05-java-aws-projects/
```

| My Project Name                            | Existing Idea                    | Possible AWS Services                                               | Related Day(s)  | Cost Risk          | Status  |
| ------------------------------------------ | -------------------------------- | ------------------------------------------------------------------- | --------------- | ------------------ | ------- |
| Java AWS Architecture Notes                | Java deployment decision notes   | ECS, EC2, Lambda, ALB, API Gateway                                  | Day 50          | Planning Only      | Future  |
| Spring Boot Banking System Deployment      | Java backend showcase            | ECS Fargate, ECR, ALB, RDS, CloudWatch                              | Day 51 - Day 53 | Medium / High Cost | Future  |
| Money Transfer API on AWS                  | Spring Boot + Postgres project   | ECS Fargate, RDS PostgreSQL, ALB, CloudWatch                        | Day 54          | Medium / High Cost | Future  |
| Async API Aggregator on AWS                | Weather/news/stock async API     | Lambda or ECS, API Gateway, Secrets Manager, CloudWatch             | Day 55          | Medium Cost        | Future  |
| Java AWS Decision Notes                    | API Gateway vs ALB for Java apps | API Gateway, ALB, ECS, Lambda                                       | Day 56          | Planning Only      | Future  |
| Java Observability Notes                   | CloudWatch logs for Spring Boot  | CloudWatch, ECS, Lambda                                             | Day 57          | Log Cost Awareness | Future  |
| Java CI/CD Pipeline                        | CI/CD for Spring Boot on AWS     | GitHub Actions, ECR, ECS, CodeBuild, CodePipeline                   | Day 58          | Medium Cost        | Future  |
| InspiroBot.AI Cloud Version                | Motivational quote scheduler     | Lambda/API Gateway or ECS, DynamoDB, S3, CloudWatch, AI API/Bedrock | Day 59          | Cost Review Needed | Future  |
| DailyQuote API on AWS                      | Quote API project                | Lambda or ECS, API Gateway, DynamoDB/RDS                            | Future          | Medium Cost        | Future  |
| TeamPulse Cloud Deployment                 | Team/project tracking app        | ECS, RDS, S3, CloudWatch, IAM                                       | Future          | Medium / High Cost | Future  |
| Employee Insights Java 8 TDD Cloud Version | Java 8/TDD project               | Lambda or ECS, DynamoDB/RDS, CloudWatch                             | Future          | Medium Cost        | Future  |
| Personal Portfolio Website                 | Developer portfolio              | S3, CloudFront, Route 53, ACM                                       | Future          | Low / Medium Cost  | Planned |

---

## Project Documentation Standard

Each project should include:

```text
README.md
cost-estimate.md
cleanup-checklist.md
screenshots/
```

Optional files:

```text
architecture.md
troubleshooting.md
interview-notes.md
youtube-script.md
linkedin-post.md
```

---

## Project README Should Cover

Each project README should answer:

* What is the project?
* Why does it matter?
* Which AWS services are used?
* What architecture is followed?
* What steps were performed?
* What was the outcome?
* What was the cost?
* How was cleanup handled?
* What did I learn?

---

## Current Project Focus

Current completed project:

```text
01-beginner-friendly-projects/billing-alerts-setup/
```

Next safe project:

```text
01-beginner-friendly-projects/iam-user-group-setup/
```

Next portfolio-style project:

```text
04-portfolio-projects/aws-cloud-resume-challenge/
```
