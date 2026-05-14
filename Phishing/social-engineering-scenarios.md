# 🎭 Social Engineering Scenarios

> Real-world attack scenarios with psychological analysis. Study these to recognize manipulation in real life.

---

## Scenario 1: The IT Emergency Call

**Setting:** You're an employee at a mid-sized company. It's 4:45 PM on a Friday.

**The Call:**
> *"Hi, this is David from the IT Security team. We've detected a critical intrusion on the network. We're in emergency lockdown mode and need to remotely verify all employee machines immediately. I need your Windows login credentials to run a remote diagnostic. This is extremely urgent — our firewall is being actively attacked right now."*

### Psychological Tactics Used:
- **Urgency**: "Critical intrusion," "actively attacked right now"
- **Authority**: Impersonating IT Security department
- **Time pressure**: End of day Friday (people want to go home)
- **Fear**: Framing it as a network emergency affecting everyone

### Why People Fall For It:
- Employees trust IT staff who "know their systems"
- Fear of being responsible for missing an alert
- Friday afternoon cognitive fatigue = reduced scrutiny
- Desire to be seen as a cooperative team player

### How to Respond:
1. Do NOT give your credentials. IT staff can reset passwords — they never need yours
2. Ask for their employee ID and department extension
3. Hang up and call the IT helpdesk using the official internal directory number
4. Report the call to IT Security immediately

---

## Scenario 2: The CEO Wire Transfer

**Setting:** You're a finance assistant. Your CEO is traveling internationally.

**The Email:**
> *"Hi [Name], I'm in meetings all day and can't be reached. We're closing an urgent deal and I need you to wire $25,000 to this account immediately. Please keep this confidential for now — I'll explain everything when I'm back. Account details: [foreign bank account]. Please confirm when done. — Robert Chen, CEO"*

### Psychological Tactics Used:
- **Authority**: CEO impersonation (highest trust level)
- **Urgency**: "urgent deal," must be done "immediately"
- **Secrecy**: "keep this confidential" — prevents victim from asking others
- **Reciprocity**: Implies trust by giving employee an important task
- **Isolation**: "I can't be reached" prevents verification

### Why People Fall For It:
- Fear of disappointing or slowing down the CEO
- Excited to be trusted with an important task
- "Confidential" instruction prevents natural verification
- Email display names can be faked to look exactly like the CEO's

### How to Respond:
1. NEVER transfer money based solely on an email request
2. Call the CEO directly on their known personal phone number
3. Verify through a second internal contact (e.g., CFO or their PA)
4. Check: is the email from the CEO's real company address or a similar-looking fake?

---

## Scenario 3: The "Package Waiting" SMS

**The Text:**
> *"INDIA POST: Your package (Tracking: IN-2847-XK) could not be delivered. Pay ₹25 customs fee to release: indiapost-customs-fee.in"*

### Why It Works:
- People order things online constantly — it's plausible
- Small amount (₹25) doesn't trigger financial caution
- Official-sounding language and tracking number
- Shortened/plausible-looking URL

### What Actually Happens:
The payment form captures your full card details. The ₹25 "fee" is just to verify the card works. Then hundreds or thousands of rupees are charged.

### How to Respond:
1. Visit India Post's official website (`indiapost.gov.in`) directly
2. Enter the tracking number there to see if the package exists
3. Never pay fees through a link in an SMS

---

## Scenario 4: The LinkedIn Fake Recruiter

**The Message:**
> *"Hi [Name]! I saw your profile and you're exactly what Amazon is looking for. We have a remote role at $150K/year — no interview needed, just complete our background screening. Fill out this form: [Google Form link requesting SSN, address, bank account for direct deposit setup]"*

### Psychological Tactics Used:
- **Flattery + Ego**: "exactly what we're looking for"
- **Greed**: Exceptionally high salary
- **Scarcity implied**: "no interview needed" suggests limited availability
- **Legitimacy cues**: Amazon brand, professional language

### Identity Theft Data Harvested:
- Full name + address (dossier building)
- SSN (for financial fraud and identity theft)
- Bank account (for direct theft or money mule setup)

### Red Flags:
- Legitimate companies don't skip interviews
- SSN and bank details are never collected via Google Forms for recruitment
- Check if the recruiter has a verified LinkedIn profile with work history

---

## Scenario 5: The Fake Tech Support Pop-Up

**What Appears:**
A full-screen browser popup with a Windows Error logo and alarm sounds:
> *"⚠️ CRITICAL ERROR — YOUR COMPUTER IS INFECTED! Call Microsoft Support immediately: 1800-XXX-XXXX. Do NOT shut down your computer."*

### Why It Works:
- Visual + audio alarm creates immediate panic
- "Do NOT shut down" prevents the obvious fix
- Looks official with Windows styling
- Targets less tech-savvy users who may not know what a real Windows error looks like

### What Happens If You Call:
1. "Technician" asks for remote access (using TeamViewer or AnyDesk)
2. They pretend to "fix" the virus while installing real malware
3. They charge $299–$999 for the "service"
4. They steal financial data visible on your screen

### How to Respond:
1. Press `Alt + F4` or `Ctrl + W` to close the browser tab
2. If browser is frozen: `Ctrl + Shift + Esc` → Task Manager → End Task on browser
3. Run a real antivirus scan from Windows Defender
4. Microsoft will NEVER show a phone number in an error message
