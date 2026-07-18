# AWS Cloud Basics Glossary
This file contains simple AWS terms I learn during my AWS Cloud Journey 2026.

---
## AWS

Amazon Web Services.

A cloud platform that provides computing, storage, networking, security, database, monitoring, and many other services.

---

## Root User

The main AWS account user with full access to everything in the account.

The root user should not be used for daily AWS work.

---

## MFA

Multi-Factor Authentication.

MFA adds an extra security step during login.

---

## AWS Budget

A cost management feature used to set spending limits and receive alerts.

AWS Budgets help track spending and avoid unexpected charges.

---

## Billing Dashboard

The AWS area where usage, charges, budgets, and cost information can be viewed.

---

## Region

An AWS Region is a geographical area where AWS resources can be created and managed.
A geographical area where AWS has multiple data center locations.

Example:

```text
Europe (London) - eu-west-2
```
---

## Availability Zone

An Availability Zone is an isolated data center location inside an AWS Region.

Availability Zones help improve availability and fault tolerance.

---

## Edge Location

An Edge Location is used by services like CloudFront to deliver content closer to users.

---

## Shared Responsibility Model

An AWS security model that explains what AWS is responsible for and what the customer is responsible for.

AWS is responsible for security **of** the cloud.

The customer is responsible for security **in** the cloud.

---

## IAM

Identity and Access Management.

IAM is used to manage users, groups, roles, and permissions in AWS.

---

## Lambda

A serverless compute service that runs code without managing servers.

---

## CloudWatch

A monitoring and logging service in AWS.

It helps collect logs, metrics, and alarms.

---

## S3

Simple Storage Service.

S3 is used to store files and objects.

---

## Access Key

A credential used for programmatic access to AWS.

Access keys should never be committed to GitHub.

---

## Secret Access Key

A private key used together with an access key.

This must be kept secret and never shared publicly.

---

## API Gateway

A service used to create, publish, and manage APIs.

It is commonly used with Lambda to build serverless APIs.

---
