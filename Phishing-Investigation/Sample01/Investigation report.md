Date: Wed, 05 Nov 2025 14:27:33 -0500

Subject: " =?UTF-8?B?VHJ1c3QgQWNjb3VudCBTdXNwZW5kZWQgLSBBY3Qgbm93IQ==?= " - It is encoded in MIME as it starts with =? and ends with ?= 
			"UTF-8 Character set used". B - indicates base64.

Decode Subject: Trust Account Suspended - Act now!

From: security@trust-bank-support.com
To: student@example.edu

Reply to: urgent-response@trustbank-alert.co

Sender IP : 203[.]0[.]113[.]55
Sender Host: mail.phishy-server.net

Message ID: <CAK1234567890@example-phish.net>

URLs : hxxps[://]trust-bank-secure[.]com/verify/?id=87654321

Attachments : MD5, SHA1, SHA256 - NONE

Description: A Phishing email mimicking a bank account suspension alert. It features spoofed headers, urgent language, and a fake verification link to demonstrate a look-alike domain 

Artifact Analysis:

Sender Analysis: The From address uses a different domain from the reply-to domain. This is a common phishing tactic to redirect replies to an attacker-controlled address.

URL Analysis: The URL from the plain text and from the HTML are identical. But the Trust Bank in the URLs has a hyphenated version, trust-bank. Real Trust Bank has trustbank.com. This is a common attack to trick users.

Sender Mail Client Analysis: X-mailer says Microsoft Outlook 16.0, but the sending server is Postfix, which is an open source tool for sending bulk emails

Verdict: The email exhibits multiple indicators of phishing, including 
1. MIME-encoded subject line
2. Urgent and manipulative language
3. Suspicious Message-ID, X-mailers, and Reply-Path
4. Embedded link pointing to a non-trustworthy domain.

Defense Actions: 
1. Immediate containment: Block the Sender IP and Domain at the email gateway.
2. User Protection: Notify the users not to interact with or click the link. If clicked, initiate a password reset.
3. Threat Intelligence: Submit email artifacts(URLs, payloads) to internal threat intel platform.
4. Monitor and Detection: Deploy detection rules for similar subject lines and encoded headers.
5. Awareness and Training: Use this case in phishing simulation or awareness training.


