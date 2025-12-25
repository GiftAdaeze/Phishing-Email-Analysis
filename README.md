# Phishing Email Analysis Report

## Overview
This report documents the analysis of three real-world phishing emails.  
The goal is to break down how these emails attempt to manipulate users, identify indicators of compromise (IOCs), assess risk levels, and explain why an average user could realistically fall for them.

This project focuses on *attacker mindset, human factors, and practical detection*, not just theory.

---

## Scope of Analysis
For each phishing email, the following were analyzed:
- Sender manipulation
- Social engineering techniques used
- Indicators of compromise (IOCs)
- Risk level
- Why the attack could fool an average user

---

## Sample 1: Fake LastPass Security Alert

**Claimed Service:** LastPass  
**Email Theme:** Security breach notification  
**Screenshot:**  
![LastPass Phishing Email](https://drive.google.com/uc?export=view&id=1LkcY28YfrGdrPfBbr-ryRCKlPwsxV2h2)

### Sender Manipulation
- Sender name appears as **LastPass**
- Email address uses a misleading domain:  
  `LastPass@secure-monitor.com`
- Domain is unrelated to the official LastPass domain

### Social Engineering Technique Used
- **Fear and urgency**
- Claims user vault data was accessed
- Suggests immediate action to “confirm” account safety

### Indicators of Compromise (IOCs)
- Non-official sender domain
- Requests user to re-enter login credentials
- Generic greeting: *“Dear LastPass User”*
- External link claiming to be a “secure website”

### Risk Level
**High:**

This targets a password manager account, which could expose multiple credentials if compromised.

### Why This Would Fool an Average User
- LastPass is a trusted security brand
- The email references a realistic breach scenario
- Many users expect security alerts to request verification
- Fear of password exposure lowers user skepticism

---

## Sample 2: Fake Netflix Payment Suspension

**Claimed Service:** Netflix  
**Email Theme:** Billing issue / account on hold  
**Screenshot:**  
![Netflix Phishing Email](https://drive.google.com/uc?export=view&id=1Eq9Ks1oeVbiqgcvB92tMtgVtLcnx8NYh)

### Sender Manipulation
- Netflix branding and layout closely mimicked
- Professional design and familiar color scheme
- Appears similar to legitimate Netflix billing emails

### Social Engineering Technique Used
- **Urgency and service disruption**
- Threatens loss of access to entertainment service
- Pushes user to act quickly to “restore” account

### Indicators of Compromise (IOCs)
- Generic greeting: *“Hi Dear”*
- Call-to-action button: *“UPDATE ACCOUNT NOW”*
- External payment update link
- Sense of urgency without specific billing details

### Risk Level
**Medium to High:**

Risk increases if users reuse passwords or enter card details.

### Why This Would Fool an Average User
- Netflix billing issues are common
- Users are conditioned to fix payment problems quickly
- Visual branding reduces suspicion
- Emotional attachment to service access

---

## Sample 3: Fake Bank of America Login Alert

**Claimed Service:** Bank of America  
**Email Theme:** New device login + suspicious transactions  
**Screenshot:**  
![Bank of America Phishing Email](https://drive.google.com/uc?export=view&id=1NU_9vcvFNdNomTzpfiF9y49Ml5SrYGe2)

### Sender Manipulation
- Uses a bank-like sender name
- Domain: `trust.ameribank7.com`  
  (Not an official Bank of America domain)

### Social Engineering Technique Used
- **Fear, authority, and urgency**
- Mentions unauthorized login and transactions
- Encourages immediate password reset

### Indicators of Compromise (IOCs)
- Fake domain imitating bank branding
- Private IP address listed: `192.168.0.1`
- Generic greeting: *“Dear account holder”*
- Suspicious password reset link

### Risk Level
**Very High:**

Targets direct financial accounts and credentials.

### Why This Would Fool an Average User
- Banks are high-trust institutions
- Mention of transactions creates panic
- Many users don’t understand IP addressing
- Immediate action feels like damage control

---

## Key Takeaways
- Phishing relies more on **psychology than technology**
- Brand trust is heavily exploited
- Urgency consistently lowers critical thinking
- Visual legitimacy often overrides technical verification

---

## Skills Demonstrated
- Email threat analysis
- Social engineering detection
- IOC identification
- Risk assessment
- Attacker mindset analysis

---

## Disclaimer
All samples are used strictly for educational and research purposes.
No real credentials were submitted during analysis.

---
