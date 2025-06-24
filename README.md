# 🛡️ Phishing Email Analysis

## 🎯 Objective

The objective of this task is to analyze a phishing email sample and identify phishing indicators by examining both the email content and its technical headers.

---

## 🛠️ Tools Used

- MXToolbox Email Header Analyzer
- Any text editor for documenting findings

---

## 🔍 Analysis Steps

### 1️⃣ Examine Sender Address

- Verify if the sender’s email domain matches the legitimate organization.
- Check for domain misspellings or slight manipulations.
- Verify if free email services are used for official communication.

### 2️⃣ Analyze Email Headers

- Inspect the full email headers to review:
  - Sender’s actual IP address.
  - SPF (Sender Policy Framework) validation.
  - DKIM (DomainKeys Identified Mail) validation.
  - DMARC (Domain-based Message Authentication) validation.
  - Received mail servers path.

### 3️⃣ Review Hyperlinks

- Check if displayed URLs match the actual destination links.
- Verify for URL redirections or hidden malicious domains.

### 4️⃣ Check for Attachments

- Verify the type of attachment.
- Check if the attachment contains executable or potentially malicious files.

### 5️⃣ Assess Language & Tone

- Look for urgency, fear tactics, or threats designed to prompt immediate action.
- Review for generic greetings instead of personalized salutations.

### 6️⃣ Review Spelling & Grammar

- Identify spelling errors, grammatical mistakes, or poorly written content that is often present in phishing attempts.

### 7️⃣ Evaluate Visual Content

- Check for poorly designed logos, low-quality images, or mismatched branding.

---



