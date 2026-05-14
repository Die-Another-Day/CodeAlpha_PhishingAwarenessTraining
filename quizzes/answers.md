# ✅ Quiz Answers & Explanations

---

## Section A: MCQ Answers

### Q1 — Answer: C) Delete it and report it as phishing

**Explanation:** The sender domain `paypall.com` (double 'l') is a typosquatted fake domain. Real PayPal emails come from `@paypal.com` only. The urgency about account suspension is a classic fear tactic. Never click links in suspicious emails — go directly to the site by typing the URL in your browser. Reporting helps your email provider protect others.

---

### Q2 — Answer: B) It is specifically targeted at one individual using their personal information

**Explanation:** Spear phishing is highly targeted. Attackers research their victim beforehand — they may use your real name, your employer, your recent purchases, or details from social media to make the email appear completely legitimate. This makes it far more convincing (and dangerous) than mass phishing emails that use generic greetings.

---

### Q3 — Answer: D) Smishing

**Explanation:** SMS-based phishing = **Smishing** (SMS + Phishing). The attack uses a shortened URL (`bit.ly`) to disguise the real destination, which would lead to a credential-harvesting or malware site. Never click shortened links in SMS messages from unknown senders. Verify delivery status directly on the retailer's official website.

---

### Q4 — Answer: C) `login.microsoftonline.com`

**Explanation:**
- `microsoft-login-verify.com` — Fake: Microsoft doesn't use hyphenated subdomains like this
- `login.mlcrosoft.com` — Fake: "mlcrosoft" is a typosquat (swapped letters)
- `login.microsoftonline.com` ✅ — Real: This is Microsoft's official authentication domain
- `ms365-secure-portal.net` — Fake: `.net` and hyphenated format are red flags

**Key rule:** Always check the root domain (the part just before `.com`/`.net`). For Microsoft, it must be `microsoft.com` or `microsoftonline.com`.

---

### Q5 — Answer: B) Hang up immediately. Banks NEVER ask for OTPs.

**Explanation:** This is a **vishing (voice phishing)** attack, often combined with SIM swapping. OTPs are One-Time Passwords — they are generated specifically for a transaction or login. If you read the OTP to someone, you are authorizing THEIR action (e.g., a money transfer). Banks, tech companies, and legitimate services ALL explicitly state: "Do not share this OTP with anyone, including our staff." There are zero exceptions.

---

### Q6 — Answer: C) Scarcity and Urgency

**Explanation:** "Only 2 spots left" creates **scarcity** (limited availability), and "Act NOW" and "expires" create **urgency** (time pressure). Together they trigger the brain's System 1 (fast, instinctive) thinking, bypassing the logical analysis that would otherwise identify the manipulation. The countermeasure is the "10-second rule" — pause, breathe, think before acting.

---

### Q7 — Answer: B) Whaling / Business Email Compromise (BEC) attack

**Explanation:** **Whaling** targets high-level executives (CEOs, CFOs). **Business Email Compromise (BEC)** involves impersonating an executive to trick employees into sending money or sensitive data. This is one of the most financially damaging forms of phishing — the FBI reports BEC has cost businesses over $50 billion globally. Always verify financial requests through a secondary channel (call the CEO directly on their known number).

---

### Q8 — Answer: B) It requires an additional verification factor the attacker doesn't have

**Explanation:** MFA adds a second layer beyond your password. Even if an attacker has your exact username and password, they cannot log in without also having your:
- Phone (for SMS OTP or authenticator app)
- Physical hardware key (e.g., YubiKey)
- Biometric (fingerprint/face)

This is why MFA reduces account compromise risk by **99.9%** according to Microsoft's internal data.

---

### Q9 — Answer: C) `Coffee!Rain#Book9Tree`

**Explanation:**
- `password123` — Extremely common, in every hacker's dictionary attack list
- `JohnSmith1990` — Personal information that can be guessed from social media
- `Coffee!Rain#Book9Tree` ✅ — A **passphrase**: long (20+ characters), mixed case, symbols, numbers, memorable but random
- `qwerty@2024` — Keyboard pattern + current year = predictable

**Passphrase rule:** Pick 4–5 random words, add symbols and numbers. Length is more important than complexity.

---

### Q10 — Answer: B) Disconnect from internet, scan for malware, change passwords, alert IT

**Explanation:** Immediate response steps after clicking a phishing link:
1. **Disconnect** from the internet immediately to prevent malware communication
2. **Do not enter any credentials** on any page that opened
3. **Run a full antivirus/malware scan** (Windows Defender, Malwarebytes)
4. **Change passwords** for any accounts associated with your current session
5. **Alert your IT/security team** — they need to know in case the network is affected
6. **Monitor accounts** for unusual activity over the next 30 days

---

## Section B: Scenario Answers

---

### Scenario 1: The Urgent IT Request

**Three Red Flags:**
1. Email domain `company-helpdesk.net` — your company's IT would email from `@yourcompany.com`
2. Attachment is a `.exe` (executable) file — legitimate patches come through official update systems
3. "2 hours or account locked" — artificial urgency designed to rush action without thinking

**Attack Type:** Spear Phishing with Malware Delivery. The `.exe` likely contains a trojan or ransomware.

**What To Do:**
1. Do NOT download or run the attachment
2. Do NOT click any links
3. Forward the email to your real IT security team immediately
4. Call your IT helpdesk using their official internal number to verify
5. Report it as phishing to your email security system

---

### Scenario 2: URL Analysis

| URL | Status | Reason |
|-----|--------|--------|
| `https://www.amazon.com/orders/tracking` | ✅ SAFE | Exact official domain |
| `https://amazon-order-confirm.site/track` | ❌ SUSPICIOUS | Different domain — `.site` + hyphenated "amazon" |
| `https://login.live.com/login.srf` | ✅ SAFE | `live.com` is Microsoft's official OAuth domain |
| `https://microsoft-account-verify.net/login` | ❌ SUSPICIOUS | Hyphenated fake domain, `.net` not `.com` |
| `https://paypal.com/myaccount/summary` | ✅ SAFE | Exact official PayPal domain |
| `https://paypai.com/verify` | ❌ SUSPICIOUS | "paypai" — lowercase 'i' replacing 'l' — classic visual trick |

---

### Scenario 3: LinkedIn Fake Recruiter

**Social Engineering Tactics Used:**
- **Urgency**: "starts next week" — no time to think
- **Too-good-to-be-true bait**: $200K salary for immediate hire without interview
- **Authority**: Claims to be from Apple — high-prestige company
- **Scarcity**: Implied limited opportunity

**Information Being Stolen:**
- SSN (Social Security Number) — for identity theft
- Bank account details — for financial fraud
- Personal references — for further targeted attacks

**What To Do:**
1. Do not fill out the form
2. Search for the recruiter's name on LinkedIn — verify they actually work at Apple
3. Report the profile to LinkedIn as fake/spam
4. Legitimate Apple job applications happen at `jobs.apple.com` only
5. Never submit SSN or bank details via Google Forms to a stranger
