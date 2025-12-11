# Analyzing Security Incident Logs to Detect Potential Cyber Threats

This project analyzes Microsoft security incident logs to identify **high-risk user accounts, organizational vulnerabilities, off-hours anomalies, and MITRE ATT&CK techniques associated with severe alerts**. Using **SQL** for data transformation, **Excel** for exploration, and **Tableau** for visualization, the project highlights **indicators of compromise and gaps in incident response**.

---

## Dashboards

**Dashboard 1 — High Risk Account Overview**  
- Top accounts generating high-severity alerts  
- Unresolved alerts by organization  
- Off-hours access anomalies  
- Average time between alerts  

**Dashboard 2 — MITRE ATT&CK Behavior Analysis**  
- Most frequent attack categories  
- Highest-risk MITRE techniques by organization  
- Accounts tied to specific techniques  
- Most severe attack categories  

---

## Repository Structure

/1_sql   → Data cleaning & analysis queries

/2_data   → Cleaned datasets & Tableau CSVs

/3_visualizations   → Dashboard screenshots

/4_paper   → Final project report


---

## Tools Used

- ![SQL](https://img.shields.io/badge/SQL-Blue?style=flat-square)
- ![BigQuery](https://img.shields.io/badge/BigQuery-LightBlue?style=flat-square)
- ![Excel](https://img.shields.io/badge/Excel-Green?style=flat-square)
- ![Tableau](https://img.shields.io/badge/Tableau-LightBlue?style=flat-square)
- ![Kaggle](https://img.shields.io/badge/Kaggle-Blue?style=flat-square)
- ![GitHub](https://img.shields.io/badge/GitHub-Black?style=flat-square)

---

## Key Insights (Short Version)

- One account (673934) generated an **abnormally high volume of high-severity alerts at near-instant intervals**.  
- Organizations 738, 73, and 116 show clusters of **unresolved ransomware, phishing, and execution-based attacks**.  
- Off-hours access patterns suggest **automated activity or malware beaconing**.  
- MITRE techniques such as **T1486 (Ransomware), T1566.002 (Phishing), and T1059.001 (PowerShell)** appeared repeatedly across high-risk organizations.  

Full details are in the final report.

---

## Full Report

The complete capstone report is available here:  

/4_paper/security_capstone_report.pdf

It includes **methodology, research questions, findings, dashboards, and recommendations**.
