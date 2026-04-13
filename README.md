# PMT Strategic Fleet Forensic Audit (2021-2023)

> **Interactive Version:** [View the Live Tableau Story]( https://public.tableau.com/views/PMT25-HubForensicAuditAnalysisCompleteExecutiveReport2021-2023/PMTForensicAuditFinalReport)


<img width="680" height="546" alt="image" src="https://github.com/user-attachments/assets/63edaa2d-4f0b-461e-bd4f-77e4d71d06f1" />


# PMT-25-Hub-Forensic-Audit-Analysis-Complete-Executive-Report-2021-2023-
Forensic Audit of ₦62.5B fleet project (2021-23). Analysis of 25 hubs via Python &amp; Tableau. Identified 15% operational leakage &amp; categorized performance tiers (A-D) to isolate integrity risks in insolvent regional hubs.
📊 Forensic Audit & Fleet Performance Analysis (2021–2023)
## Links: https://public.tableau.com/views/PMT25-HubForensicAuditAnalysisCompleteExecutiveReport2021-2023/PMTForensicAuditFinalReport

https://colab.research.google.com/drive/1DfWhWz4TS2C-Ix3ZFkoYA9I_guph-U4x?usp=sharing

Peace Mass Transit – 25 Operational Hubs Project

🔍 Project Overview

This project analyzes the operational and financial performance of 25 transport hubs under a ₦62.5 billion fleet investment program by Peace Mass Transit. Each hub was assigned 100 buses under a 5-year repayment model, with 30% of monthly revenue allocated toward capital recovery.

The goal of this project is to evaluate:

Operational efficiency
Capital recovery performance
Cost structure and leakages
Risk exposure across hubs
🎯 Business Problem

Despite significant investment, performance varied widely across hubs. Management required insights to:

Identify high-performing vs underperforming hubs
Detect financial leakages
Evaluate repayment sustainability
Support strategic operational decisions
🧠 Approach (Data Analytics Process)

1. Ask
Which hubs are meeting repayment targets?
What factors drive performance differences?
Where are operational inefficiencies occurring?

2. Prepare
Collected multi-source data from:
ERP systems
Maintenance Tracking System (MTS)
Live Ticketing systems

3. Process
Cleaned and standardized data using Python (Pandas) in Google Colab
Handled missing values and ensured consistency across 36 months (2021–2023)

4. Analyze
Created key metrics:
Repayment Velocity Index
Fuel-to-Income Ratio
Operating Cost Ratio
Loan Dependency Index
Performed anomaly detection and comparative analysis across hubs
5. Share
Built an interactive dashboard in Tableau
Enabled dynamic filtering by hub for real-time KPI analysis

6. Act
Provided strategic recommendations based on findings
📈 Key Insights
Top Performers: Lagos (Mazamaza), Port Harcourt
Strong cost control and repayment performance
High-Risk Hubs: Yeneogoa, Jos
Operating below break-even with high loan dependency
Operational Leakage:
~15% of expenses identified as unexplained inefficiencies
Performance Gap:
Driven more by management effectiveness than market conditions
🛠 Tools & Technologies
Python (Pandas) – Data Cleaning & Analysis
Google Colab – Data Processing Environment
SQL – Data Structuring & Querying
Tableau – Data Visualization & Dashboarding
Excel / CSV – Data Storage & Preparation

📊 Dashboard Features
Interactive hub selection (dynamic KPI updates)
Revenue, cost, and profit breakdown
Performance ranking across hubs
Risk and loan dependency analysis

🚀 Recommendations
Replicate high-performing hub models
Restructure underperforming hubs
Enforce cost control measures
Improve operational governance
Reallocate fleet assets for optimal utilization

📁 Project Structure
/data
   - raw_data.csv
   - cleaned_data.csv

/notebooks
   - data_cleaning.ipynb
   - analysis.ipynb

/dashboard
   - tableau_dashboard.twbx

/outputs
   - summary_report.pdf

