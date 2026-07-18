# Day 01 Troubleshooting - AWS Account Security

## Issue 1: Signature Expired Error

### Error Message

```text
Signature expired
```

---

## Root Cause

My laptop time was different from the actual current time.

AWS requests are time-sensitive. If the local system time or timezone is incorrect, AWS may reject console or API actions because the request timestamp is not valid.

---

## Fix Applied

1. Checked MacBook date and time settings
2. Corrected the system time
3. Signed out from AWS
4. Closed old AWS tabs
5. Signed in again
6. Reopened security credentials
7. Enabled MFA successfully

---

## Status

Resolved.
