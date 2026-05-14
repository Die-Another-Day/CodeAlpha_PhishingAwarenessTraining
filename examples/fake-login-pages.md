# 🌐 Fake Login Pages — Detection Guide

> How attackers clone real websites and what to look for.

---

## How Fake Login Pages Are Built

Attackers use three main techniques:

**1. HTTrack / Website Cloning** — Download an entire website's HTML, CSS, and images. Modify the form action to send credentials to attacker's server instead.

**2. Phishing Kits** — Pre-built packages available on dark web marketplaces. A "PayPal kit" includes all HTML, CSS, and PHP needed to stand up a convincing fake in minutes.

**3. Evilginx2 / Reverse Proxy** — Advanced technique that proxies the REAL site. Victim interacts with actual website, but attacker intercepts credentials AND session tokens in real time. Bypasses MFA.

---

## Side-by-Side: Real vs Fake

### PayPal
| Feature | Real | Fake |
|---------|------|------|
| URL | `paypal.com` | `paypal-secure-verify.com` |
| SSL Certificate | Issued to PayPal, Inc. | Often generic or issued to attacker |
| Domain Age | 25+ years | Days to weeks |
| Login Flow | Redirects to `paypal.com/signin` | Captures on fake page, redirects after |

### Microsoft
| Feature | Real | Fake |
|---------|------|------|
| URL | `login.microsoftonline.com` | `microsoft365-verify.net` |
| Email check step | Queries Microsoft's real auth system | Local page, always proceeds |
| Error messages | Accurate Microsoft error codes | Generic or missing |

---

## 5 Ways to Verify a Website is Real

**1. Check the URL Bar First**
The most important thing. Look at the full URL carefully before entering any credentials.
- Real: `https://www.amazon.in/`
- Fake: `https://amazon-india-deals.com/login`

**2. Click the Padlock → View Certificate**
In Chrome: Click padlock → "Connection is secure" → "Certificate is valid" → Check "Issued to" field. Should show the company name (e.g., "Amazon.com, Inc.")

**3. Use WHOIS Domain Lookup**
Visit `whois.domaintools.com` and search the domain. A legitimate site will be years old. A phishing site registered 3 days ago is a red flag.

**4. Google the Company Directly**
Instead of clicking a link, Google the company name. The official site will appear at the top.

**5. Bookmark Important Sites**
Create bookmarks for: your bank, PayPal, Gmail, Microsoft, Amazon, government portals. Navigate via bookmark only — never via email links.

---

## URL Anatomy — Know What to Check

```
https://secure.paypal.com/signin?country=US

[1]    [2]    [3]         [4]
https:// = Protocol (must be HTTPS)
secure = Subdomain (can be anything — doesn't validate legitimacy)
paypal.com = ROOT DOMAIN ← THIS IS WHAT MATTERS
/signin = Path
?country=US = Parameters
```

**The root domain is everything between the last two dots before the first `/`.**

- `paypal-secure.verify-login.com` → Root domain: `verify-login.com` ❌
- `secure.paypal.com` → Root domain: `paypal.com` ✅
- `paypal.fakephishing.com` → Root domain: `fakephishing.com` ❌

---

## Real-World Fake Sites Detected (Educational Reference)

| Target Impersonated | Fake Domain Used | Red Flag |
|--------------------|-----------------|----------|
| PayPal | `paypal-secure.net` | Different root domain |
| Netflix | `netflix-billing-update.com` | "billing-update" not in Netflix domain |
| Amazon | `amazon-package-delivery.in` | Not amazon.in |
| SBI Bank | `sbionline-banking-secure.com` | Not sbi.co.in |
| HDFC Bank | `hdfcnetbanking-secure.in` | Not hdfcbank.com |
| Google | `google-account-verify.co` | Not google.com |
| Microsoft | `microsoftsupport365.com` | Root domain not microsoft.com |
