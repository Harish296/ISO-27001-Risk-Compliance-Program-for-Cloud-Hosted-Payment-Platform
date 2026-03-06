# Pay29 Solutions - Phishing Incident Response Playbook

**Incident Type:** Phishing Attack  
**Prepared For:** Pay29 Solutions  
**Standard:** ISO 27001:2022  
**Version:** 1.0  
**Date:** March 2026  

---
## 1. Overview

This playbook provides a guide for Pay29 Solutions on how to respond to a phishing incident. It was created following a phishing attack three months ago that compromised two employee accounts and exposed the need for a documented response process.

### ISO 27001:2022 Controls Referenced

| Control | Title |
|---|---|
| A.5.24 | Incident management planning and preparation |
| A.5.25 | Assessment and decision on information security events |
| A.5.26 | Response to information security incidents |
| A.5.27 | Learning from information security incidents |
| A.5.28 | Collection of evidence |

---
## 2. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| CISO | Overall incident ownership and escalation decisions |
| IT Administrator | Technical response and system investigation |
| IAM Lead | Credential reset and access revocation |
| Compliance Officer | Documentation and evidence collection |
| Affected Employee | Report the incident and cooperate with the investigation |

---
## 3. Preparation

**ISO 27001 Control: A.5.24**

Before an incident occurs Pay29 should have the following in place:

- This playbook is documented and accessible to relevant staff
- All employees know how to report a suspicious email
- Suspicious emails should be reported to **security@pay29.com**
- Microsoft 365 security alerts are configured
- MFA is enforced on all employee accounts

---
## 4. Detection

**ISO 27001 Control: A.5.25**

A phishing incident may be detected through:

- An employee reporting a suspicious email
- Microsoft 365 flagging unusual login activity
- An employee noticing unexpected changes in their inbox
- A colleague reporting receiving a suspicious email from a Pay29 address

### Steps

1. Log the date, time and nature of the report
2. Ask the employee if they clicked any link, entered credentials or 
   downloaded any attachments
3. Assign a severity - Low, Medium, High or Critical
4. Notify the CISO if severity is High or Critical

---
## 5. Analysis

**ISO 27001 Control: A.5.25**

### Steps

1. Examine the phishing email - sender address, links and attachments
2. Check Microsoft 365 sign-in logs for any unusual login activity on 
   the affected account
3. Determine how many employees received the same email
4. Check whether any data was accessed or exfiltrated
5. Document all findings before taking any containment action

---
## 6. Containment

**ISO 27001 Control: A.5.26**

### Steps

1. Disable the compromised account in Microsoft 365
2. Revoke all active sessions for the affected account
3. Block the phishing sender domain in Microsoft 365
4. Quarantine the phishing email from all employee inboxes
5. Notify employees not to interact with the phishing email
6. Check for any unauthorized email forwarding rules and remove them

---
## 7. Eradication

**ISO 27001 Control: A.5.26**

### Steps

1. Reset the password for all compromised accounts
2. Enforce MFA on the compromised account before re-enabling it
3. Scan affected devices for malware
4. Remove any malicious inbox rules or forwarding rules
5. Block malicious URLs identified during analysis

---
## 8. Recovery

**ISO 27001 Control: A.5.26**

### Steps

1. Re-enable the compromised account only after eradication is complete
2. Brief the affected employee on what happened and what to watch out for
3. Monitor the restored account for 7 days for any unusual activity
4. Confirm whether any customer data was accessed or exposed

---
## 9. Lessons Learned

**ISO 27001 Control: A.5.27**

A post incident review should be conducted within 7 days of the incident 
being resolved. The following questions should be discussed:

- How was the incident detected and how long did it take?
- Were the response steps followed correctly?
- What could have prevented this incident?
- What controls need to be added or improved?

### Lessons Learned Log

| Field | Details |
|---|---|
| Incident ID | |
| Date of Review | |
| Root Cause | |
| What Went Well | |
| What Could Be Improved | |
| Action Items | |
| Action Owner | |
| Target Date | |

---
*This playbook was prepared for portfolio purpose only.*
