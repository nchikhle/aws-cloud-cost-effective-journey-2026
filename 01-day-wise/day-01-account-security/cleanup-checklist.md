# Day 01 Cleanup Checklist - AWS Account Security

## Goal

Confirm that no unnecessary AWS resources were created during Day 1 account security setup.

---

## Resources Created Today

| Resource        | Created? | Cost Impact | Action Required |
| --------------- |----------|-------------|-----------------|
| AWS Account     | Yes      | £0 / $0     | Keep            |
| Root MFA        | Yes      | £0 / $0     | Keep            |
| EC2 Instance    | No       | N/A         | None            |
| S3 Bucket       | No       | N/A         | None            |
| IAM User        | No       | N/A         | None            |
| Lambda Function | No       | N/A         | None            |
| API Gateway     | No       | N/A         | None            |
| Database        | No       | N/A         | None            |
| IAM User        | No       | N/A         | None            |
| Access Key      | No       | N/A         | None            |

---

## Cleanup Checklist

* [x] Confirm root MFA is enabled
* [x] Attempt Billing Dashboard check
* [x] Recheck Billing Dashboard data after refresh

* [x] Confirm no EC2 instances were created
* [x] Confirm no S3 buckets were created
* [x] Confirm no Lambda functions were created
* [x] Confirm no API Gateway APIs were created
* [x] Confirm no databases were created
* [x] Confirm no IAM users were created
* [x] Confirm no access keys were created
* [x] Confirm no paid AWS application resources are running

* [x] Record Day 1 estimated cost in Monthly Cost Tracker

---

## Billing Check

| Item                     | Status                                  |
| ------------------------ | --------------------------------------- |
| Billing Dashboard access | Attempted                               |
| Billing data visibility  | Pending / To be confirmed after refresh |
| AWS credits received     | $100                                    |
| Unexpected charges found | No                                      |
| Billing alerts setup     | Pending for Day 2                       |
| Monthly budget setup     | Pending for Day 2                       |

---

## Estimated Cost

Estimated cost for Day 1: **£0 / $0**

Reason:

Only account creation and root MFA setup were performed.

No paid AWS application resources were created.

---

## Final Status

| Item                         | Status            |
| ---------------------------- | ----------------- |
| Day 1 account security setup | Completed         |
| Root MFA                     | Enabled           |
| Paid resources created       | No                |
| Cleanup required             | No                |
| Monthly Cost Tracker         | Updated           |
| Billing safety follow-up     | Planned for Day 2 |
