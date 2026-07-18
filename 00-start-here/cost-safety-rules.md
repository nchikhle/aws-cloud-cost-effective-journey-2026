# Cost Safety Rules

This file contains the AWS cost-safety rules I follow throughout this journey.

The goal is to learn AWS confidently while avoiding accidental charges.

---

## Rule 1: Security and Billing Before Services

Before creating AWS resources, I should first:

* Enable root MFA
* Understand the Billing Dashboard
* Create a monthly budget
* Enable budget alerts
* Understand cleanup responsibility

Security and billing safety should come before EC2, S3, Lambda, API Gateway, databases, or other AWS resources.

---

## Rule 2: Check Pricing Before Creating Resources

Before creating any AWS service, ask:

* Is this free or paid?
* Is it charged hourly?
* Is it charged by storage?
* Is it charged by requests?
* Is there a free tier or credit coverage?
* What happens if I forget to delete it?

This helps avoid creating resources without understanding their cost impact.

---

## Rule 3: Track AWS Activity

After hands-on practice, record:

* Date
* Activity
* Services used
* Estimated cost
* Cleanup status
* Any unexpected cost

Daily cleanup details stay inside the day folder.

Monthly cost tracking stays inside:

```text
03-cost-tracker/
```

---

## Rule 4: Use Cleanup Checklists

Each day folder should include:

```text
cleanup-checklist.md
```

The cleanup checklist confirms whether any resources were created and whether anything needs to be deleted.

Simple rule:

```text
If I create it, I must track it.
If I no longer need it, I must clean it up.
```

---

## Rule 5: Delete Unused Resources

After practice, delete resources that are no longer needed.

Examples:

* EC2 instances
* Unused S3 buckets
* Test Lambda functions
* Unused API Gateway APIs
* Test databases
* Unused CloudWatch alarms
* Temporary access keys

Some resources may be intentionally kept, such as:

* Root MFA
* AWS budget
* Budget alerts
* Required learning IAM setup

If a resource is kept, the reason should be documented.

---

## Rule 6: Never Ignore Small Charges

Even small unexpected charges should be investigated.

If I notice an unexpected cost, I should document:

* What service caused it
* Why it happened
* Whether cleanup was needed
* How I fixed it
* How I can avoid it next time

Small cost surprises can teach important billing lessons.

---

## Rule 7: Protect Billing and Account Information

Never upload screenshots showing:

* AWS account ID
* Root email
* Personal email address
* Card details
* Billing address
* Payment method
* Invoices with private information
* Access keys
* Secret keys
* MFA QR codes
* Session tokens

Screenshots must be redacted before being added to GitHub, LinkedIn, or YouTube.

---

## Rule 8: Update the Monthly Cost Tracker

After AWS hands-on practice, update the correct monthly cost tracker file.

Recommended file format:

```text
03-cost-tracker/YYYY-MM-monthly-cost-tracker.md
```

Example:

```text
03-cost-tracker/2026-05-monthly-cost-tracker.md
03-cost-tracker/2026-06-monthly-cost-tracker.md
```

The tracker should include:

* Date
* Activity
* AWS services used
* Estimated cost
* Cleanup status
* Notes

---

## Rule 9: Prefer Low-Cost Learning First

For beginner practice, prefer free or low-cost learning tasks first.

Examples:

* IAM
* MFA
* AWS Budgets
* Billing Dashboard checks
* S3 small test files
* Lambda basic tests
* CloudWatch basic logs

Avoid expensive resources until their pricing and cleanup process are understood.

Examples to be careful with:

* NAT Gateway
* RDS
* Load Balancers
* Large EC2 instances
* Large S3 storage
* High CloudWatch log usage

---

## Rule 10: End Every Practice Session with a Cost Check

Before closing AWS Console, check:

* Billing Dashboard
* Running resources
* Cleanup checklist
* Monthly cost tracker

This creates a habit of safe AWS learning.

---

## Personal Cost Goal

My current goal is to stay as close to **£0** as possible while learning AWS fundamentals.

If cost is expected, it should be:

* planned
* tracked
* documented
* cleaned up if no longer needed

---

## Cost-Safe Learning Principle

```text
Security first.
Cost-aware always.
Hands-on carefully.
Cleanup every time.
```
