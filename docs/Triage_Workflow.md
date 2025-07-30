# Phishing Triage Workflow

This document outlines the step-by-step workflow for investigating a phishing email.

## Step-by-Step

1. **Initial Review**
   - Examine subject, sender, and time of delivery.
2. **Header Analysis**
   - Extract headers and identify anomalies.
3. **Body & Link Inspection**
   - Analyze email body, links, and attachments.
4. **IOC Extraction**
   - Identify and document IOCs (IP, email, domains, hash).
5. **Reputation Check**
   - Use VirusTotal, AbuseIPDB, URLhaus etc.
6. **Decision & Reporting**
   - Mark as phishing, report to stakeholders, and block IOCs.