# AWS Learning Roadmap

This is a flexible, cost-safe AWS learning roadmap for my **AWS Cloud Journey 2026**.

The goal is not to rush through a fixed checklist. The goal is to build real AWS confidence with security awareness, cost safety, hands-on practice, troubleshooting, cleanup discipline, interview preparation, and project documentation.

---

## Learning Principle

```text
Learn → Build → Document → Troubleshoot → Clean up → Teach
```

Every project should be attempted only after understanding:

- why I am creating it
- whether it may create cost
- how to monitor it
- how to clean it up
- whether a smaller or safer version is enough

---

## How I Will Update This Roadmap

This roadmap may change when:

- a topic needs more time
- a project becomes more important
- I discover a better learning order
- cost risk needs to be reduced
- interview preparation needs priority
- a hands-on issue teaches something valuable

Any changes should keep the same learning values:


## Phase 1 - Safe AWS Foundation

| Day | Topic | Related Project               | Cost Mindset | Status      |
|---|---|-------------------------------|---|-------------|
| Day 01 | Account Security | Account Security Setup        | Free | Completed   |
| Day 02 | Billing, Credits, and Budget Alerts | **Billing Alerts Setup**      | Free | Completed     |
| Day 03 | Cloud Basics | Cloud Basics Reference Notes  | Free | Planned |
| Day 04 | IAM Basics | **IAM User and Group Setup**  | Free | Planned     |16-19 TWS
| Day 05 | IAM Least Privilege | IAM Read-Only Access Setup    | Free | Planned     |
| Day 06 | AWS CLI Setup | **AWS CLI + S3 Bucket Setup** | Low Cost | Planned     |TWS
| Day 07 | Week 1 Review | Week 1 Foundation Summary     | Free | Planned     |

---

## Phase 2 - Beginner AWS Services

| Day | Topic | Related Project                                         | Cost Mindset | Status |
|---|---|---------------------------------------------------------|---|---|
| Day 08 | EC2 Basics | **Hello World Website on EC2**  UserData LaunchTamplate | Medium cost; stop/terminate required | Planned |06
| Day 09 | EC2 Security Groups and SSH | EC2 Secure Access Notes                                 | Medium cost; avoid leaving instance running | Planned |22/26
| Day 10 | ECR Basics | **Docker Image Push to ECR**  TWS                       | Low/medium cost; cleanup images | Planned |
| Day 11 | RDS Basics | **RDS SQL Server Basics**                               | High cost; cost review required | Future |
| Day 12 | DynamoDB Basics | **DynamoDB Basic Table**                                | Low cost if small usage | Planned |
| Day 13 | S3 Basics | **S3 Object Storage Basics**                            | Low cost; delete test objects | Planned |
| Day 14 | SNS Basics | **SNS Email Notification Demo**                         | Low cost; confirm subscriptions | Planned |
| Day 15 | Lambda Basics | **Lambda Add Two Numbers**                              | Low cost if minimal invocations | Planned |
| Day 16 | S3 + CloudFront Basics | **Static Webpage with S3 and CloudFront**               | Low/medium cost; cleanup distribution if needed | Planned |
| Day 17 | AWS Config Basics | **AWS Config Managed Rule Dem**                         | Cost review required | Future |
| Day 18 | CloudFormation Basics | **CloudFormation Console Deployment**                   | Depends on resources created | Planned |
| Day 19 | Beginner Services Review | Beginner Projects Summary                               | Required cleanup check | Planned |

---

## Phase 3 - Multi-AWS-Service Projects

| Day | Topic | Related Project                      | Cost Mindset | Status |
|---|---|--------------------------------------|---|---|
| Day 20 | Auto Scaling Basics | **Auto Scaling Group Demo**  LB, TWS | Medium cost; EC2 resources must be cleaned up | Cost Review Needed |
| Day 21 | ECS and Fargate Basics | Fargate Container Deployment         | Medium cost; task cleanup required | Future |
| Day 22 | Aurora Basics | Aurora MySQL Database Setup          | High cost; do not start without cost estimate | Future |
| Day 23 | Step Functions Basics | Step Functions Two-Step Workflow     | Low/medium cost; small workflow only | Planned |
| Day 24 | API Gateway Basics | Serverless API with API Gateway      | Low/medium cost; watch requests/logs | Planned |
| Day 25 | CloudWatch Alarms | CloudWatch Alarm Demo   TMS          | Low/medium cost; alarm cleanup if not needed | Planned |
| Day 26 | KMS Basics | KMS Encrypted S3 Object              | Medium cost; understand key cost | Future |
| Day 27 | EFS Basics | EFS Shared File System               | Medium/high cost; cleanup required | Future |
| Day 28 | Multi-Service Review | Multi-Service Summary                | Billing and cleanup review | Planned |

---

## Phase 4 - Real-World Infrastructure

| Day | Topic | Related Project | Cost Mindset | Status |
|---|---|---|---|---|
| Day 29 | RDS Backup and Restore | SQL Server Backup and Restore on RDS | High cost; future only | Future |
| Day 30 | Terraform Basics | Terraform VPC Deployment | Cost review required | Future |
| Day 31 | VPC Public/Private Subnets | Terraform VPC Deployment | Avoid NAT Gateway unless planned | Future |
| Day 32 | NAT Gateway and Internet Gateway | Terraform VPC Deployment | NAT Gateway can create cost quickly | Future |
| Day 33 | Infrastructure Cleanup and Cost Review | Real-World Infrastructure Summary | Required cleanup review | Future |

---

## Phase 5 - Portfolio and Advanced AWS

| Day | Topic | Related Project | Cost Mindset | Status |
|---|---|---|---|---|
| Day 34 | Docker Swarm on EC2 | Docker Swarm Cluster on EC2 | Medium/high cost | Future |
| Day 35 | Amplify Basics | Basic Web App with Amplify | Cost review required | Future |
| Day 36 | AppSync and DynamoDB | Basic Web App with Amplify | Low/medium cost | Future |
| Day 37 | Bedrock Basics | Bedrock Recipe Generator | Cost review required | Future |
| Day 38 | PartyRock and Amazon Q | GenAI Apps with PartyRock and Bedrock | Cost review required | Future |
| Day 39 | Multi-Tier Architecture | Multi-Tier Highly Available Web App | High cost; future only | Future |
| Day 40 | WordPress HA Architecture | Highly Available WordPress App | High cost; future only | Future |
| Day 41 | CodePipeline and CodeBuild | Continuous Delivery Pipeline | Medium cost | Future |
| Day 42 | Elastic Beanstalk | Continuous Delivery Pipeline | Medium cost | Future |
| Day 43 | EKS Basics | Web App on EKS | High cost; future only | Future |
| Day 44 | Step Functions at Scale | Large-Scale Data Processing Workflow | Cost review required | Future |
| Day 45 | SageMaker Basics | SageMaker Fraud Detection Solution | High cost; future only | Future |
| Day 46 | Kinesis Basics | Serverless Data Processing on AWS | Cost review required | Future |
| Day 47 | Cloud Resume Challenge Planning | AWS Cloud Resume Challenge | Medium cost; can be optimized | Future |
| Day 48 | IoT Core and Rekognition | IoT and AI Video Monitoring System | Cost review required | Future |
| Day 49 | Advanced Portfolio Review | Advanced Project Summary | Billing and cleanup review | Future |

---

## Phase 6 - Java on AWS Track

| Day | Topic | Related Project | Cost Mindset | Status |
|---|---|---|---|---|
| Day 50 | Java App Deployment Options on AWS | Java AWS Architecture Notes | Planning only | Future |
| Day 51 | Dockerize Spring Boot App | Spring Boot Banking System Deployment | Local first | Future |
| Day 52 | Push Spring Boot Image to ECR | Spring Boot Banking System Deployment | Cleanup images | Future |
| Day 53 | Deploy Spring Boot App to ECS Fargate | Spring Boot Banking System Deployment | Medium cost; cleanup tasks | Future |
| Day 54 | RDS PostgreSQL for Spring Boot | Money Transfer API on AWS | Medium/high cost | Future |
| Day 55 | Secrets Manager Basics | Async API Aggregator on AWS | Cost review required | Future |
| Day 56 | API Gateway vs ALB for Java Apps | Java AWS Decision Notes | Planning only | Future |
| Day 57 | CloudWatch Logs for Spring Boot | Java Observability Notes | Log cost awareness | Future |
| Day 58 | CI/CD for Spring Boot on AWS | Java CI/CD Pipeline | Medium cost | Future |
| Day 59 | InspiroBot.AI Cloud Architecture | InspiroBot.AI Cloud Version | Planning first | Future |
| Day 60 | Final Portfolio Review | Java AWS Portfolio Summary | Cost and cleanup review | Future |


Megha projects:
Serverless