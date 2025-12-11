# cybersecurity-incident-analysis
Analyzing Security Incident Logs to Detect Potential Cyber Threats
This project analyzes Microsoft security incident logs to identify high-risk user accounts, organizational vulnerabilities, off-hours anomalies, and MITRE ATT&CK techniques associated with severe alerts. Using SQL for data transformation, Excel for exploration, and Tableau for visualization, the project highlights indicators of compromise and gaps in incident response.

Dashboard 1 — High Risk Account Overview
* Top accounts generating high-severity alerts
* Unresolved alerts by organization
* Off-hours access anomalies
* Average time between alerts
Dashboard 2 — MITRE ATT&CK Behavior Analysis
* Most frequent attack categories
* Highest-risk MITRE techniques by organization
* Accounts tied to specific techniques
* Most severe attack categories

Repository Structure
/sql → Data cleaning & analysis queries  
/data → Cleaned datasets & Tableau CSVs  
/visualizations → Dashboard screenshots  
/paper → Final project report  

Tools Used
* SQL (BigQuery syntax)
* Excel
* Tableau
* GitHub
* Kaggle Dataset: Microsoft Security Incident Prediction

Key Insights (Short Version)
* One account (673934) generated an abnormally high volume of high-severity alerts at near-instant intervals.
* Orgs 738, 73, and 116 show clusters of unresolved ransomware, phishing, and execution-based attacks.
* Off-hours access patterns suggest automated activity or malware beaconing.
* MITRE techniques such as T1486 (Ransomware), T1566.002 (Phishing), and T1059.001 (PowerShell) appeared repeatedly across high-risk organizations.
Full details are in the final report.

Report
The full capstone report is available in:

/paper/security_capstone_report.pdf

It includes methodology, research questions, findings, dashboards, and recommendations.
