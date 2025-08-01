<p align="center">
  <img src="https://raw.githubusercontent.com/Adity77mx/soc1-phishing-triage/main/phishing_banner.png" alt="Phishing Investigation Banner" style="width:100%; border-radius:12px;">
</p>

<h1 align="center" style="color:#00FF00;">🕵️‍♂️ Phishing Email Investigation Triage</h1>
<p align="center"><i>A Realistic SOC Analyst Training Experience – Powered by Splunk & Forensics</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Level-SOC%20Tier%201-green?style=for-the-badge&logo=github" alt="SOC Tier 1 Badge"/>
  <img src="https://img.shields.io/badge/Category-Phishing-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Made%20by-Aditya%20Mathur-orange?style=for-the-badge"/>
</p>

---

---

<img src="screenshots/doom_portfolio_soc1.png" alt="Dr Doom SOC1 Portfolio Banner" style="width:100%; border-radius:12px;"/>


> ⚔️ **Welcome to the Dark Side of Email Defense**  
> This investigation exposes the sinister layers of a real-world phishing attack.  
> Dive into the evidence, connect the clues, and uncover the threat actor’s true intent.

---

 <img src="https://imgproxy.attic.sh/insecure/f:webp/q:90/w:750/plain/https://attic.sh/doa9027xcl7gy75l0rcesjqfvcn6" width="45" alt="Dr Doom Emoji">This is my project


<p>
  <img 
    src="https://imgproxy.attic.sh/insecure/f:webp/q:90/w:750/plain/https://attic.sh/65xxe772gm676dtgtgc9lfclnpa6" 
    alt="🧠 Doctor Doom Face Emoji" 
    width="40" 
    style="vertical-align: middle; border-radius: 12px; margin-right: 10px;" />
  <strong style="font-size: 100px; vertical-align: middle;">Case Objective</strong>
</p>











Analyze and respond to a real phishing attempt using real-world evidence like `.eml` files and screenshots.  
Determine intent, impact, and appropriate action using SOC triage principles.



# 🛡️ Phishing Email Triage Report (SOC Level 1 Portfolio)

A complete investigation walkthrough of a suspicious phishing email, analyzed from a SOC Level 1 perspective.  
This project mimics how an entry-level security analyst would triage and report phishing threats inside a SOC environment.

📄 **Read the Full Report** → [Phishing_Triage_Investigation_Report.md](Phishing_Triage_Investigation_Report.md)

---

## 📌 Summary

This report demonstrates the **triage** process of a real-world suspicious email using open-source tools, threat intelligence, and manual analysis.

The key objectives:
- Identify phishing indicators
- Perform header analysis
- Check URLs/domains
- Map behavior to MITRE ATT&CK
- Provide risk score and recommendations

---
## 📁 Folder Structure

```
soc1-phishing-triage/
├── evidence/
│   ├── phishing_email.eml
│   ├── email_body_screenshot.png
│   ├── header_analysis_screenshot.png
│   ├── ioc_virustotal_screenshot.png (optional)
├── docs/
│   ├── IOC_cheatsheet.md
│   ├── Header_analysis_guide.md
│   └── Triage_Workflow.md
├── README.md
```

## 🧠 Skills Demonstrated

| Category            | Skills Applied                                                                 |
|---------------------|--------------------------------------------------------------------------------|
| 📥 Email Triage     | Header analysis, sender verification, domain reputation checks                 |
| 🔗 Threat Intel     | URL reputation lookup, sandbox checks, MITRE technique mapping                 |
| ⚙️ Analyst Thinking | Evidence-based conclusion, documentation, risk scoring, recommendation writing |

---

## 🖼️ Screenshots

Here are some highlights from the report:

### 🧪 Header Analysis Sample  
<img src="https://raw.githubusercontent.com/Adity77mx/soc1-phishing-triage/main/email_header_sample.png" width="250"/>


---

### 🔗 URL Intelligence Check  
<img src="https://raw.githubusercontent.com/Adity77mx/soc1-phishing-triage/main/url_analysis_sample.png" width="250"/>

---

## 📊 Visual Walkthrough

<img src="https://raw.githubusercontent.com/Adity77mx/soc1-phishing-triage/main/Phishing_Investigation_Flowchart.png" width="400"/>





## 📂 Report Contents

- Overview of the incident
- Technical indicators of phishing
- Visual snapshots of analysis steps
- MITRE mapping to `T1566.001` (Spearphishing via Email)
- Final summary + risk rating

---

## 📘 Why This Matters

This type of investigation is a **day-one task** for entry-level SOC Analysts.  
This report shows you're capable of:

- Reading between the lines of suspicious emails
- Using public tools like `MXToolbox`, `VirusTotal`, and header parsers
- Explaining findings clearly to non-technical stakeholders

---

## 🚀 Future Improvements

- Add `.eml` file parsing via Python
- Automate IOC extraction
- Connect to Splunk or a SIEM simulator

---

## ✅ How to View the Report

Just click 👉 [Phishing_Triage_Investigation_Report.md](Phishing_Triage_Investigation_Report.md)  
No software required — pure markdown, viewable in any browser or GitHub app.

---


## MITRE MAPPING

<p align="center">
<img src="https://raw.githubusercontent.com/Adity77mx/soc1-phishing-triage/main/phisihing_mitre_mapping.png" width="400"/>
</p>

---

🛡️ Made with patience, precision & passion for cyber defense.

## 🕵️ Evidence Collected

🔹 **Phishing Email File (.eml)**  
[📥 phishing_email.eml](./evidence/phishing_email.eml)

🔹 **Screenshots**  
- 📸 [Email Body](./evidence/email_body_screenshot.png)  
- 📸 [Header Analysis](./evidence/header_analysis_screenshot.png)
  

🔹 **Supporting Docs**  
- 📄 [IOC Cheat Sheet](./evidence/IOC_cheatsheet.md)  
- 📄 [Header Analysis Guide](./evidence/Header_analysis_guide.md)  
- 📄 [Triage Workflow](./evidence/Triage_Workflow.md)

---

## 🧠 Summary of Investigation

- 🚩 **3 Suspicious Indicators** were detected
- 🎯 Confirmed Tactic: **Credential Harvesting**
- ✅ Final Verdict: **Malicious Email**
- 🛡️ Suggested Action: Quarantine and educate recipient

---

## 🔚 Conclusion
This hands-on phishing triage simulation highlights how a SOC Level 1 analyst can investigate real threats using headers, IOCs, and threat intel — validating an email as **malicious** using structured reasoning.

---

## 🤝 Contribution

This project is part of the portfolio of [Aditya Mathur](https://www.linkedin.com/in/aditya-m-7crb3b77b3). Contributions and feedback are welcome.

---

