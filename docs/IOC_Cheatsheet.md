# IOC Cheatsheet

This cheatsheet provides quick reference to common Indicators of Compromise (IOCs) used during phishing triage.

## Common IOC Types

| Type            | Description                                  | Example                          |
|-----------------|----------------------------------------------|----------------------------------|
| Email Address   | Sender or reply-to address                   | suspicious@example.com           |
| IP Address      | Originating IP of email                      | 192.168.1.5                      |
| URL/Domain      | Link embedded in email or attachment         | http://malicious[.]site/login   |
| File Hash       | MD5/SHA256 of a malicious file               | e99a18c428cb38d5f260853678922e03 |
| Subject Line    | Email subject used in phishing               | "Urgent: Reset Your Password"    |

## Tips for Effective IOC Usage
- Always validate IOCs using open-source intelligence (OSINT) tools.
- Consider the context and correlation of IOCs, not just standalone values.