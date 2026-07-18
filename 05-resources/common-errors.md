# AWS Common Errors

This file tracks AWS errors I face during my learning journey and how I fix them.

---

## Error: Signature Expired

### Error Message

```text
Signature expired
```

---

## Where It Happened

This happened while enabling MFA from the AWS root user security credentials page.

---

## Meaning

AWS rejected the request because the timestamp was too old or incorrect.

AWS requests are time-sensitive. If the local system time or timezone is incorrect, the request can fail.

---

## Possible Causes

- Laptop time is wrong
- Browser session expired
- VPN or proxy issue
- Stale AWS Console tab
- System timezone mismatch

---

## Fix

Steps:

1. Correct system date and time
2. Sign out from AWS
3. Close AWS tabs
4. Open a new browser window
5. Sign in again
6. Retry the action

---

## My Learning

AWS requests are time-sensitive.

Even if the AWS account is fine, incorrect local system time can cause console actions to fail.

Cloud troubleshooting is not always only about AWS services. Sometimes the issue can be related to local device settings, browser session, VPN, or timezone configuration.

---

## Status

Resolved during Day 01 account security setup.

Related file:

```text
01-days/day-01-account-security/troubleshooting.md
```
