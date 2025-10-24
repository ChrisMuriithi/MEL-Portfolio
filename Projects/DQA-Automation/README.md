# Data Quality Assurance (DQA) Automation Project: Enhancing Data Integrity Across EDARP’s 14 Facilities  

*Automating data validation, cleaning, and performance monitoring to improve accuracy, accountability, and efficiency across EDARP’s health programs.*

---

## 🧩 Project Overview
The **Data Quality Assurance (DQA) Automation Project** was developed to **streamline and automate** data validation and quality checks across **Eastern Deanery AIDS Relief Program (EDARP)** facilities.  

Previously, DQA relied on **manual Excel-based reviews**, which were time-consuming, inconsistent, and error-prone. This project replaced those processes with a fully automated framework built using **SQL Server**, **Python**, and **Power BI**, enabling real-time detection of missing data, inconsistencies, and indicator mismatches across HIV/TB, MCH, and OPD programs.  

As the **System Architect and M&E/ICT Lead**, I designed the full automation pipeline — from rule definition to visualization — ensuring compliance with **PEPFAR’s MER guidance**, **Kenya MOH standards**, and institutional data governance protocols.

---

## 🎯 Core Objectives
- Automate data validation and indicator verification across all 14 EDARP facilities  
- Reduce manual workload and human error in DQA reviews  
- Provide management with **real-time visibility** of data completeness and consistency  
- Strengthen accountability and continuous improvement through system-driven feedback loops  

---

## 🧰 Languages & Utilities Used
| Tool / Platform | Purpose |
|------------------|----------|
| **SQL Server** | Stored procedures for validation, aggregation, and anomaly detection |
| **Python (Pandas, NumPy, Regex)** | Data cleaning, automation, and validation rule execution |
| **Power BI** | Visualization of DQA performance and facility-level metrics |
| **Excel / Power Query** | Reconciliation and QA cross-checks |
| **Git / GitHub** | Version control and script management |
| **NVivo** | Qualitative analysis of DQA feedback from facilities |

---

## 🖥️ Environment / Platforms Used
- **Microsoft SQL Server** – Central DQA data warehouse  
- **Python environment** – Automated ETL and validation jobs  
- **Power BI Service** – Real-time DQA visualization  
- **Azure File Storage** – Automated backup of logs and reports  
- **Ecare EMR** – Primary data source for HIV/TB, MCH, and OPD indicators  

---

## 🧭 Implementation Walkthrough

### 1. Rule Definition & Mapping  
Developed a comprehensive **DQA Validation Rule Matrix** covering completeness, timeliness, consistency, and uniqueness.  
Mapped rules to specific indicators (e.g., validating `TX_CURR` vs. `TX_NEW + TX_RTT`).

### 2. Automation Script Design  
Built **Python and SQL scripts** to auto-flag outliers, missing data, and logical inconsistencies.  
Configured **SQL Server Agent jobs** for nightly execution and automated refreshes.

### 3. Error Logging & Tracking  
Created a **dynamic Error Log Table** capturing facility, variable, anomaly type, and resolution status.  
Added **timestamped audit trails** for full accountability.

### 4. Dashboard Development  
Designed **Power BI dashboards** with color-coded visualizations showing:  
- Error trends by facility  
- Data completeness and timeliness  
- Indicator accuracy (EMR vs DHIS2)  
- DQA audit completion and status tracking  
Automated **email summaries** delivered weekly to facility teams.

### 5. Feedback & Correction Loop  
Facility M&E teams received **automated DQA reports**, implemented corrections, and synced data for re-validation.  
Resolved issues were automatically logged as “closed” within the audit trail.

### 6. Capacity Building  
Trained **22 data officers** and M&E staff on dashboard interpretation, troubleshooting, and maintenance of validation scripts.

---

## 📦 Key Outputs / Deliverables
- ✅ **Automated DQA Engine** – SQL + Python-based framework for nightly data checks  
- ✅ **Power BI DQA Dashboard** – Real-time visualization of data integrity metrics  
- ✅ **Validation Rule Library** – 60+ program-specific rules and logic tests  
- ✅ **Facility DQA Tracker** – Auto-generated Excel follow-up reports  
- ✅ **DQA SOP Manual** – Standardized guide for automation, correction, and reporting workflows  

---

## 📈 Results & Impact
| Outcome | Result |
|----------|---------|
| **Data Accuracy** | Reporting discrepancies reduced by **71%** across 14 facilities |
| **Timeliness** | DQA cycle time reduced from **5 days → 6 hours** |
| **Efficiency** | Saved approximately **160 staff hours per month** |
| **Accountability** | Introduced **audit trail logs** with user-level tracking |
| **Reliability** | Achieved **98% alignment** with DHIS2 quarterly data |

---

## 💡 Lessons Learned & Future Improvements
- **Challenge:** Initial validation rules generated false positives due to strict thresholds  
- **Improvement:** Introduced **adaptive thresholds** and dynamic indicator ranges  
- **Next Steps:**  
  - Implement **machine learning models** to predict facilities likely to generate errors  
  - Add **chatbot notifications** (via Teams/WhatsApp) for instant anomaly alerts  
  - Expand DQA automation to include **finance and HR datasets** for full institutional oversight  

---

## 📂 Visuals and Documentation
Suggested repository structure:


---

## 🏷️ Tags / Keywords
`#DataQuality` `#Automation` `#PowerBI` `#Python` `#SQLServer`  
`#MEL` `#DigitalHealth` `#DataAnalytics` `#EDARP` `#Kenya`

---

## 🧾 Badges
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Ecare](https://img.shields.io/badge/Ecare%20EMR-003399?style=for-the-badge)
![Kenya](https://img.shields.io/badge/Kenya-006600?style=for-the-badge&logo=googleearth&logoColor=white)
![EDARP](https://img.shields.io/badge/EDARP-003399?style=for-the-badge)

---

## 👤 Author
**By [Christopher Muriithi Mwangi](https://www.linkedin.com/in/christopher-mwangi-894265b0)**  
📧 [nomiskris@gmail.com](mailto:nomiskris@gmail.com)  
💻 [@ChrisMuriithi](https://github.com/ChrisMuriithi)  
🎓 [Google Scholar](https://scholar.google.com/citations?user=isM9thcAAAAJ&hl=en)
