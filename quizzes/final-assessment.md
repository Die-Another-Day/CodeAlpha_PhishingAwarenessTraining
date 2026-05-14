# 🎓 Final Assessment — Phishing Awareness Certification

> **Format:** 10 MCQ + 2 Scenario Challenges | **Time:** 15 minutes | **Pass Mark:** 80% (10/12 points)

---

## PART A: Multiple Choice (1 point each)

---

### 1. Which of the following best defines "phishing"?

- A) A technique for recovering deleted files from a hard drive
- B) A social engineering attack where attackers impersonate legitimate organizations to steal sensitive data
- C) A method of encrypting data for secure transmission
- D) A firewall configuration technique

---

### 2. A cybercriminal sends a highly personalized email to the CFO of a Fortune 500 company, using their name, title, and recent company news. This is called:

- A) Mass Phishing
- B) Smishing
- C) Whaling
- D) Vishing

---

### 3. You receive an SMS from "HDFC Bank" saying: *"Your account is blocked. Verify now: bit.ly/hdfc-verify"*. The MOST important red flag is:

- A) The message is too short
- B) The link is a shortened URL not from HDFC's official domain
- C) The message came in the afternoon
- D) The message didn't include your account number

---

### 4. Which MFA method is MOST resistant to phishing attacks?

- A) SMS OTP (text message code)
- B) Email OTP
- C) Security questions
- D) Hardware security key (e.g., YubiKey)

---

### 5. An attacker calls you pretending to be Microsoft tech support and says your computer is infected. They ask for remote access. This is:

- A) Spear Phishing
- B) Vishing (Voice Phishing)
- C) Smishing
- D) Pharming

---

### 6. Which of these passwords is MOST secure?

- A) `Admin@2024`
- B) `P@ssw0rd`
- C) `Mango_River_Cloud_47!`
- D) `MyName1990#`

---

### 7. Ransomware delivered via phishing typically does which of the following?

- A) Speeds up your computer
- B) Encrypts your files and demands payment for the decryption key
- C) Automatically sends your emails to the attacker
- D) Changes your desktop wallpaper

---

### 8. You're browsing and see a green padlock (HTTPS) on a website. This means:

- A) The website is completely safe and legitimate
- B) The connection is encrypted, but the site may still be a phishing page
- C) The website is owned by a verified company
- D) Your credentials are stored securely on that site

---

### 9. Which of the following is the correct way to verify a suspicious email from your bank?

- A) Click the link to see if it looks like your bank's website
- B) Reply to the email asking if it's legitimate
- C) Close the email, open a new browser tab, and go to your bank's official website directly
- D) Forward the email to a colleague and ask their opinion

---

### 10. Your colleague clicks a phishing link and ransomware starts encrypting files on the shared network drive. What is the IMMEDIATE priority?

- A) Screenshot the ransomware note for documentation
- B) Pay the ransom quickly before more files are encrypted
- C) Disconnect the affected machine from the network immediately and alert IT security
- D) Run a disk cleanup on the affected computer

---

## PART B: Scenario Challenges (1 point each)

---

### Challenge 1: Email Forensics

Analyze this email and answer the questions below:

```
FROM:    verify@netflix-account-billing.com
TO:      member@email.com
SUBJECT: Your Netflix payment failed — Update payment info now

Dear Netflix Member,

Your payment of $15.99 failed. Your account will be SUSPENDED 
in 48 hours unless you update your billing information.

[UPDATE PAYMENT METHOD]

Netflix Customer Support
© Netflix, Inc. 2024
```

**Question A:** List ALL the red flags you can identify (minimum 3 for full credit).

**Question B:** What type of attack is this, and what is the attacker's goal?

**Question C:** Write the exact steps you would take after receiving this email.

---

### Challenge 2: Real-World Decision Making

Read each situation and choose the CORRECT response:

**Situation A:**
Your manager sends you a WhatsApp message from an unknown number: *"I'm in a meeting and my phone died. Can you urgently buy 5 × ₹5,000 Amazon gift cards and send me the codes? I'll reimburse you immediately."*

Which response is correct?
- i) Buy the gift cards — your manager needs urgent help
- ii) This is a gift card scam. Call your manager on their known number to verify before taking any action.
- iii) Send a WhatsApp reply asking for their employee ID
- iv) Buy 2 gift cards to be safe and wait for confirmation

**Situation B:**
You're setting up a new online account. The site asks you to choose security questions. Which approach is MOST secure?

- i) Use real answers your family could verify (e.g., real mother's maiden name)
- ii) Use fake, random answers stored in your password manager (e.g., Mother's maiden name: "Purple Dinosaur 42")
- iii) Skip security questions by refreshing the page
- iv) Use the same answers for all security questions across all sites

---

## Scoring

| Score | Result |
|-------|--------|
| 12/12 | 🏆 Phishing Expert — Outstanding! |
| 10–11 | ✅ CERTIFIED — Phishing Aware |
| 8–9 | ⚠️ Review recommended — Retake suggested |
| Below 8 | ❌ Please revisit the training module |

---

## Answer Key (For Instructors Only)

1. B | 2. C | 3. B | 4. D | 5. B | 6. C | 7. B | 8. B | 9. C | 10. C

**Challenge 1A:** Red flags: `netflix-account-billing.com` is not `netflix.com`; generic "Dear Netflix Member"; "SUSPENDED in 48 hours" artificial urgency; suspicious CTA link; payment issues are handled in-app, not via email

**Challenge 1B:** Credential + payment harvesting phishing. Goal: steal credit card details entered on a fake payment page.

**Challenge 1C:** Do NOT click links. Mark as phishing. Open Netflix.com directly in a new tab. Check account status there. Forward to `phishing@netflix.com`.

**Challenge 2A:** ii — Gift card scam. Verify on known number first.

**Challenge 2B:** ii — Fake random answers stored in password manager prevent social engineering via personal knowledge.
