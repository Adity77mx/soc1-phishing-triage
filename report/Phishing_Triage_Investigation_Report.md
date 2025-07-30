\# 🛡️ Phishing Triage SOC Investigation -- Portfolio Project

\## 📌 Objective Simulate a phishing triage investigation as a SOC Level
1 Analyst, analyzing email evidence and documenting findings in a
professional, job-ready format.

\-\--

\## 📨 Email Metadata - \*\*From:\*\* \`info@citibank-alerts.com\` -
\*\*To:\*\* \`employee@victimcorp.com\` - \*\*Subject:\*\* \`Action
Required: Unusual Login Attempt\` - \*\*Date:\*\* \`Jul 26, 2025\`

\-\--

\## 🔎 Key Indicators of Phishing \| Indicator \| Description \|
\|\-\-\-\-\-\-\-\-\--\|\-\-\-\-\-\-\-\-\-\-\-\--\| \| \`Display Name
Spoofing\` \| Email appears from Citibank but domain is suspicious \| \|
\`Urgency Tone\` \| Uses scare tactics -- "unusual login attempt" \| \|
\`Link Destination\` \| Hovering reveals fake login URL
\`http://citibank-update-alerts.com/login.php\` \| \| \`No
Personalization\` \| Generic greeting "Dear User" \| \|
\`Attachment/File\` \| Malicious PDF with hidden redirect embedded \|

\-\--

\## 🔗 Link Analysis - \*\*URL:\*\*
\`http://citibank-update-alerts.com/login.php\` - \*\*Domain Age:\*\*
Registered 2 days ago - \*\*Hosted In:\*\* Russia - \*\*WHOIS:\*\*
Redacted info, known phishing infrastructure - \*\*VT Result:\*\* 9/72
AV engines flag the URL as malicious

\-\--

\## 📎 Attachment Analysis - \*\*Filename:\*\*
\`SecureLoginUpdate.pdf\` - \*\*Behavior:\*\* When opened, redirects
user to phishing website - \*\*VT Scan Result:\*\* 5/66 engines flag
this as a threat - \*\*YARA Match:\*\* \`PDF.Phish.FakeBanking\`

\-\--

\## 🧠 Analyst Judgment \> This is a \*\*confirmed phishing attempt\*\*
leveraging spoofed branding, urgency tactics, and redirect-based PDF
delivery. The indicators are consistent with credential harvesting
campaigns targeting corporate logins.

\-\--

\## ✅ Recommended Actions - Block domain:
\`citibank-update-alerts.com\` - Notify affected user and advise
credential reset - Submit IOC to threat intel platform - Search for
similar emails in mail gateway logs - Add YARA signature to endpoint
protection

\-\--

\## 📂 Tags \`#SOC1\` \`#PhishingTriage\` \`#EmailAnalysis\`
\`#PortfolioProject\` \`#ThreatIntel\`

\-\--

\## 📅 Date Created July 29, 2025

\## 👨‍💻 Author Aditya Mathur GitHub:
\[github.com/adityamathur-sec\](https://github.com/adityamathur-sec)
