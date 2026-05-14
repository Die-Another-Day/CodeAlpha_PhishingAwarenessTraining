# 📧 Phishing Email Examples

> Real-world style phishing email scenarios with full analysis. These are **educational simulations** — not real emails.

---

## Example 1: Fake PayPal Email

```
FROM:    security-alert@paypall-verify.com
TO:      you@yourmail.com
SUBJECT: ⚠️ URGENT: Your PayPal account has been LIMITED

Dear Valued Customer,

We have detected suspicious activity on your PayPal account. 
To avoid permanent suspension, you must verify your identity immediately.

Your account access will be PERMANENTLY CLOSED in 24 hours if no action is taken.

[VERIFY MY ACCOUNT NOW]

PayPal Security Team
© PayPal Inc. 2024 — All Rights Reserved
```

### 🔴 Red Flags
| Flag | Why It's Dangerous |
|------|--------------------|
| `paypall-verify.com` (double 'l') | Typosquatting — not PayPal's real domain |
| "Dear Valued Customer" | Generic greeting — PayPal always uses your real name |
| "PERMANENTLY CLOSED in 24 hours" | Artificial urgency — classic fear tactic |
| `[VERIFY MY ACCOUNT NOW]` button | Links to a credential-harvesting page |
| Sent from a non-paypal.com domain | Real PayPal emails come from `@paypal.com` only |

### 🛡️ How to Identify
- Hover over any link — it will show a suspicious non-PayPal URL
- Log in directly at **paypal.com** (type it yourself) — your account status is shown there
- Real PayPal security alerts include your full name and last 4 digits of linked card

### ✅ What To Do
1. Do NOT click any links
2. Mark as **Phishing/Spam** in your email client
3. Forward to: `spoof@paypal.com`
4. Delete the email

---

## Example 2: Fake Microsoft Account Alert

```
FROM:    account-security@microsoft-365-alerts.net
TO:      john.doe@company.com
SUBJECT: Action Required: Your Microsoft 365 License Has Expired

Hello John,

Your Microsoft 365 subscription has expired. Your files and emails 
will be DELETED within 48 hours unless you renew immediately.

Account: john.doe@company.com
License: Microsoft 365 Business (EXPIRED)
Action Required: Renew before deletion occurs

[RENEW NOW — SECURE YOUR FILES]

Microsoft Support Team
Microsoft Corporation
One Microsoft Way, Redmond, WA 98052
```

### 🔴 Red Flags
| Flag | Why It's Dangerous |
|------|--------------------|
| `microsoft-365-alerts.net` | Fake domain — real Microsoft uses `microsoft.com` |
| "Files will be DELETED in 48 hours" | Scare tactic to force immediate action |
| Fake corporate footer | Stolen address to appear legitimate |
| Urgency + authority combination | Dual psychological manipulation |

### 🛡️ How to Identify
- Check your actual Microsoft admin portal at **admin.microsoft.com**
- Real Microsoft renewal emails link to `microsoft.com` domains only
- Your IT department would handle license renewals — not individual emails

### ✅ What To Do
1. Forward to your IT/Security team immediately
2. Report to Microsoft: `phish@office365.microsoft.com`
3. Do not click any links or provide credentials

---

## Example 3: Fake Bank Alert

```
FROM:    security@secure-hdfc-banking-alert.com
TO:      customer@email.com
SUBJECT: [ALERT] Suspicious Transaction Detected on Your Account

Dear Account Holder,

A transaction of ₹49,999 has been initiated from your account to 
an unknown beneficiary. If you did NOT authorize this:

Transaction ID: TXN8827364910
Amount: ₹49,999.00
Beneficiary: UNKNOWN
Time: Today, 11:42 AM

[BLOCK THIS TRANSACTION NOW]

If you do not respond within 30 minutes, the transaction will be processed.

HDFC Bank Security Team
Toll-Free: 1800-XXX-XXXX (Fake)
```

### 🔴 Red Flags
| Flag | Why It's Dangerous |
|------|--------------------|
| `secure-hdfc-banking-alert.com` | Not HDFC's real domain (`hdfcbank.com`) |
| "30 minutes or transaction processes" | Extreme urgency — bypasses rational thinking |
| "BLOCK THIS TRANSACTION" button | Links to fake banking portal to steal credentials |
| Fake toll-free number | Clicking calls an attacker posing as bank support |

### 🛡️ How to Identify
- Call your bank using the number on the **back of your debit/credit card**
- Check your actual banking app — real transactions show there
- Banks never ask for passwords or OTPs to block transactions

### ✅ What To Do
1. Do NOT click the link or call the number in the email
2. Open your bank app directly and check your statement
3. Call your bank using the official number from their website
4. Report the email to your bank's fraud department

---

## Example 4: Fake Internship/Job Offer Scam

```
FROM:    hr.recruitment@google-careers-hiring.com
TO:      student@college.edu
SUBJECT: Congratulations! You've Been Selected for Google Internship 2024

Dear Candidate,

After reviewing thousands of applications, we are pleased to inform you 
that you have been SELECTED for Google's Summer Internship 2024!

Position: Software Engineering Intern
Stipend: $5,000/month
Start Date: Immediate

To confirm your slot, please:
1. Fill out the attached form with your personal details
2. Pay a ₹2,000 security deposit (refundable)
3. Submit your Aadhaar/ID card, bank account details

Slots are LIMITED — confirm within 24 hours!

Google HR Team
```

### 🔴 Red Flags
| Flag | Why It's Dangerous |
|------|--------------------|
| `google-careers-hiring.com` | Fake — Google uses `careers.google.com` |
| Asking for a "security deposit" | Legitimate companies NEVER ask for money |
| Requests Aadhaar + bank details | Identity theft attempt |
| "Selected without applying" | You never applied — major red flag |
| Unrealistically high stipend | Too good to be true = always suspicious |

### 🛡️ How to Identify
- Verify job offers through the company's official careers page
- Never pay money to get a job or internship
- Call the company's official HR number to verify

### ✅ What To Do
1. Do NOT pay any deposit or share personal documents
2. Report to the National Cyber Crime portal (cybercrime.gov.in in India)
3. Warn classmates/college about the scam

---

## Example 5: Fake OTP Scam (Vishing)

```
PHONE CALL SCENARIO:

Caller: "Hello, I'm calling from SBI Bank. 
         My name is Rahul Sharma, Employee ID: SBI-2847. 
         We've detected fraud on your account.
         
         To block it, I need to verify your identity. 
         I'm sending you an OTP — please read it to me."

Victim: Receives OTP (actually for a money transfer)

Caller: "Thank you. Your account is now secured."

RESULT: ₹50,000 transferred from victim's account
```

### 🔴 Red Flags
| Flag | Why It's Dangerous |
|------|--------------------|
| Unsolicited call claiming to be from bank | Banks don't call asking for OTPs |
| "I'm sending you an OTP" | The OTP is for THEIR action, not verification |
| Creates urgency — "fraud detected" | Forces victim to act without thinking |
| Asks you to read OTP aloud | OTPs are one-time auth codes — sharing = authorizing |

### 🛡️ How to Identify
- **Banks NEVER ask for OTPs.** Full stop. No exceptions.
- OTP messages always say "Do not share with anyone, including bank staff"
- If suspicious: hang up, call your bank's official number

### ✅ What To Do
1. Hang up immediately
2. Call your bank using the official number on their website
3. Report to: cybercrime.gov.in or 1930 (India Cyber Helpline)

---

## Example 6: Fake LinkedIn Recruiter Phishing

```
FROM:    talent@linkedln-recruiter-pro.com
TO:      your@email.com
SUBJECT: Exclusive Job Opportunity — Senior Developer @ Amazon

Hi [Your Name],

I came across your profile and was impressed by your experience. 
Amazon is looking for a Senior Developer urgently and you're a PERFECT fit.

Salary: $180,000/year + Remote
Start: Immediately

To proceed, please:
1. Login with your LinkedIn credentials to verify your profile
2. Complete a quick form

[ACCESS EXCLUSIVE JOB PORTAL]

Best regards,
Sarah Johnson
Senior Talent Acquisition | Amazon Hiring
```

### 🔴 Red Flags
| Flag | Why It's Dangerous |
|------|--------------------|
| `linkedln-recruiter-pro.com` | Typo: "linkedln" not "linkedin" |
| Asks for LinkedIn login on external site | Credential harvesting — not LinkedIn's login page |
| Unrealistic salary for cold outreach | Bait to entice action without thinking |
| "Urgent" + "Immediately" | Artificial urgency |

### 🛡️ How to Identify
- Legitimate recruiters contact you ON LinkedIn, not via random email
- Amazon/Google will never ask you to login via a third-party site
- Check the recruiter's actual LinkedIn profile — do they exist?

### ✅ What To Do
1. Do not click any links or enter credentials
2. Report the email and LinkedIn profile (if it exists)
3. Apply only through official company career portals

---

## Example 7: Fake Password Reset Email

```
FROM:    noreply@gmai1-security.com
TO:      you@gmail.com
SUBJECT: Your Google Account Password Was Changed

Hi,

Someone just changed the password for your Google Account. 
If this was you, no action is needed.

If this wasn't you, click below immediately to secure your account:

[SECURE MY ACCOUNT]

This link expires in 1 hour.

Google Security Team
```

### 🔴 Red Flags
| Flag | Why It's Dangerous |
|------|--------------------|
| `gmai1-security.com` (number '1') | Classic character substitution typosquatting |
| "If this wasn't you" creates panic | Designed to trigger immediate clicking |
| 1-hour expiry | Manufactured urgency |
| Not sent from `@google.com` | Real Google security emails come from `@accounts.google.com` |

### 🛡️ How to Identify
- Go directly to **myaccount.google.com** → Security → Recent activity
- Real Google security emails come from `no-reply@accounts.google.com`
- Check if the link domain is exactly `google.com` or `accounts.google.com`

### ✅ What To Do
1. Do not click the link
2. Go to myaccount.google.com directly and check your security activity
3. If your account was genuinely compromised, use Google's account recovery
4. Enable 2FA immediately if not already done
