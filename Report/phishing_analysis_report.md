# Phishing Email Analysis Report

## 1. Sample Phishing Email
Analyzed a phishing email pretending to be from Bradesco Bank offering Livelo points.

## 2. Sender Address
- From: banco.bradesco@atendimento.com.br
- Verdict: Spoofed / not official domain

## 3. Header Discrepancies
- SPF: temperror
- DKIM: none
- DMARC: temperror
=> Authentication failed

## 4. Suspicious Links
- https://blog1seguimentmydomaine2bra.me/
- Not related to Bradesco or Livelo

## 5. Urgency
- "Your points expire today!" type of language to manipulate action

## 6. Mismatched URLs
- Display text says "Click here", but actual URL is suspicious

## 7. Grammar/Spelling
- None obviously found (in Portuguese), but structure mimics professional style

## 8. Conclusion
The email is a phishing attempt using spoofed domains, failed authentication headers, urgency, and social engineering tactics.
