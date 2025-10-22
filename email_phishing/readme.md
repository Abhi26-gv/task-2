Phishing Email Analysis Report
1. Sender spoofing
•	Display Name: Microsoft Account Team
•	From Address: account-security@microsoft.com
•	Return-Path: noreply@security-alerts.example.com
•	Reply-To: support@attacker.com
•	Received from mail.attacker.com (IP 198.51.100.45)
•	Conclusion: Likely spoofed (display name matches, envelope mismatch).
2. Header discrepancies
•	SPF: fail
•	DKIM: none
•	DMARC: fail
•	Received chain shows mail from mail.attacker.com, not Microsoft servers.
•	Message-ID originates from attacker domain.
3. Suspicious links and attachments
•	Link: Verify your account → http://198.51.100.45/verify?u=user (IP, not domain, non-HTTPS)
•	Attachment: invoice.pdf (unexpected, potential malware)
4. Urgent or threatening language
•	"Your account will be suspended within 24 hours"
•	"Permanently suspended" — common social engineering tactic.
5. Grammar/spelling
•	Generic greeting: "Dear Customer"
•	Awkward phrasing: missing commas
6. Mismatched URLs
•	Visible text: Verify your account
•	Actual href: http://198.51.100.45/verify?u=user
•	Domain mismatch with sender → phishing red flag.
7. Summary of phishing traits
•	Sender impersonation
•	SPF/DKIM/DMARC failure
•	Reply-To / Return-Path mismatch
•	Suspicious IP link
•	Unexpected attachment
•	Urgent/threatening language
•	Generic greeting and grammar errors
Verdict: Highly likely phishing.

