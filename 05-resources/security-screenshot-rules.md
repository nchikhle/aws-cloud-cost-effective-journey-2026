# AWS Security Best Practices

This file contains AWS security practices I want to follow during my learning journey.

Security should start from Day 1, before creating any cloud resources.

---

## Root Account

- Enable MFA for the root user
- Do not use the root user for daily work
- Use the root user only for account-level tasks

Examples of root-level tasks:

- Billing setup
- Account recovery
- Root MFA
- Critical account settings

---

## IAM

- Create IAM users or roles for regular access
- Follow least privilege access
- Avoid giving unnecessary admin access
- Review permissions regularly
- Use groups to manage permissions where possible
- Prefer roles for service-to-service access

---

## Least Privilege Principle

Least privilege means giving only the permissions required to complete a task.

Example:

If a user only needs to view EC2 resources, they should not receive full administrator access.

---

## Credentials

Never share or upload:

- Access keys
- Secret keys
- Root email
- MFA QR codes
- Passwords
- Account ID in public screenshots

---

## Access Key Safety

Access keys should be created only when needed.

If access keys are created:

- Store them securely
- Never commit them to GitHub
- Rotate them when needed
- Delete unused access keys
- Avoid using root access keys

---

## GitHub Safety

Before uploading screenshots, hide:

- AWS account ID
- Email address
- Billing details
- QR codes
- Access keys
- Secret keys
- Private resource names if needed

---

## MFA

MFA should be enabled for important users, especially:

- Root user
- Admin users
- Any user with sensitive access

MFA adds an extra layer of protection if a password is compromised.

---

## Cost and Security Connection

Security and cost are connected.

If an AWS account is compromised, attackers may create expensive resources.

That is why account security, MFA, billing alerts, and budget checks should be set up early.

---

## Screenshot Safety Rules

Never upload screenshots showing AWS account ID, root email, access keys, secret keys, MFA QR codes, billing details, payment details, or private account information.

---

## General Rule

Security should be considered from the first day of AWS learning, not after building projects.

The safest approach is:

```text
Secure first.
Grant least privilege.
Avoid secrets in GitHub.
Review regularly.
```
