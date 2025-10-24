# Commodity and Laboratory Information Systems Integration Project: Enhancing Supply Chain Visibility and Efficiency in EDARP  

*Creating a unified digital ecosystem linking laboratory, pharmacy, and procurement systems to drive real-time visibility, efficiency, and accountability across EDARP’s health facilities.*

---

## 🧩 Project Overview
The **Commodity and Laboratory Information Systems Integration Project** unified EDARP’s **Pharmacy Information System (PIS)**, **Laboratory Information Management System (LIMS)**, and **Procurement Management System** under the **Ecare EMR platform**.  

Prior to integration, commodity and laboratory data were siloed, making it difficult to track stock levels, consumption trends, and turnaround times for test results.  
The project bridged these gaps through **database linkages**, **automated analytics**, and **real-time dashboards**, providing end-to-end visibility and accountability for all commodities and laboratory operations.  

As the **System Integration and MEL Lead**, I led the architecture design, database development, and dashboard implementation — enabling EDARP to manage stock, lab turnaround time, and procurement workflows through an integrated digital health supply chain.

---

## 🎯 Core Objectives
- Integrate **PIS**, **LIMS**, and **Procurement modules** into a unified EMR ecosystem  
- Improve visibility of **stock status**, **consumption patterns**, and **lab turnaround times (TAT)**  
- Automate data flow for **forecasting, procurement**, and **consumption reporting**  
- Strengthen **data quality**, accountability, and transparency across all facilities  

---

## 🧰 Languages & Utilities Used
| Tool / Platform | Purpose |
|------------------|----------|
| **SQL Server** | Core database development, stored procedures, and inventory tracking |
| **Python** | Data automation, analytics scripting, and visualization |
| **Power BI** | Real-time dashboards for stock, consumption, and lab TAT |
| **Excel / Power Query** | Validation of stock data and reconciliation |
| **Ecare EMR Modules** | PIS, LIMS, Procurement, and Logistics Management |
| **Power Automate / SharePoint** | Workflow automation for reorder approvals and purchase requests |

---

## 🖥️ Environment / Platforms Used
- **Ecare EMR** – hosting integrated PIS, LIMS, and Procurement modules  
- **Microsoft SQL Server** – centralized warehouse for inventory and test data  
- **Power BI Service** – dashboard environment for real-time analytics  
- **Microsoft 365 SharePoint** – repository for approval workflows and reports  
- **LAN / VPN Infrastructure** – secure network ensuring facility-level data synchronization  

---

## 🧭 Implementation Walkthrough

### 1. Baseline and Systems Mapping  
Performed a comprehensive **gap analysis** of pharmacy, lab, and procurement workflows.  
Mapped data flows from **test request → result → commodity use → stock update → reorder** for full visibility.

### 2. Database Linkage Development  
Created a **relational schema** linking LIMS, PIS, and procurement datasets.  
Developed **SQL triggers** to automatically update pharmacy stock once lab reagents were consumed.

### 3. Procurement Workflow Integration  
Linked the **procurement module** with consumption data to auto-calculate reorder levels.  
Developed stored procedures computing **consumption rate**, **buffer stock**, and **lead time** dynamically.

### 4. Dashboard and Automation Setup  
Built **Power BI dashboards** visualizing:  
- Stock on Hand (SOH) by facility  
- Monthly consumption and expiry alerts  
- Lab test turnaround time (TAT)  
- Stock-out frequency and reorder levels  
Configured **email alerts** through **Power Automate** for critical stock thresholds.

### 5. Testing and Validation  
Piloted across **5 facilities** to test synchronization and data accuracy.  
Validated consumption data against **physical stock counts** and **DHIS2 logistics reports**.

### 6. Scale-Up and Training  
Trained **pharmacists, lab officers, and procurement staff** across **14 facilities**.  
Standardized data entry and approval workflows through **SOPs**, job aids, and validation checklists.

---

## 📦 Key Outputs / Deliverables
- ✅ **Integrated Database Schema** linking LIMS, PIS, and Procurement modules  
- ✅ **SQL Triggers & Procedures** automating stock updates and reorder calculations  
- ✅ **Power BI Commodity Dashboard** for real-time monitoring  
- ✅ **Reorder Alert System** using Power Automate and SharePoint  
- ✅ **Standard Operating Procedures (SOPs)** for inventory and lab data workflows  
- ✅ **Data Quality Audit Tool** for cross-verifying digital vs physical stock records  

---

## 📈 Results & Impact
| Outcome | Result |
|----------|---------|
| **Stock Visibility** | Achieved **100% real-time stock visibility** across major facilities |
| **Reduced Stock-Outs** | Stock-outs decreased by **52%** within six months |
| **Improved Turnaround Time** | Average lab TAT reduced from **5.2 days → 1.6 days** |
| **Cost Savings** | Prevented over-procurement losses worth **Ksh 2.3M annually** |
| **Accountability** | Linked commodity use to user audit trails within EMR workflows |

---

## 💡 Lessons Learned & Future Improvements
- **Connectivity Challenges:** Some facilities faced sync delays due to unstable network links.  
- **Improvement:** Implemented **local caching** and **delayed-sync logic** for offline resilience.  
- **Next Steps:**  
  - Integrate with **KEMSA eLMIS API** for national-level reporting  
  - Introduce **predictive analytics** for stock forecasting  
  - Expand dashboards to track **cold-chain** and **waste management modules**

---

## 📂 Visuals and Documentation
Suggested repository folder structure:


---

## 🏷️ Tags / Keywords
`#HealthSupplyChain` `#LIMS` `#PIS` `#Procurement` `#SQLServer` `#PowerBI`  
`#Automation` `#DigitalHealth` `#MEL` `#EDARP` `#Kenya` `#DataDrivenDecisions`

---

## 🧾 Badges
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=microsoft-power-automate&logoColor=white)
![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=for-the-badge&logo=microsoft-sharepoint&logoColor=white)
![Ecare](https://img.shields.io/badge/Ecare%20EMR-003399?style=for-the-badge)
![Kenya](https://img.shields.io/badge/Kenya-006600?style=for-the-badge&logo=googleearth&logoColor=white)
![EDARP](https://img.shields.io/badge/EDARP-003399?style=for-the-badge)

---

## 👤 Author
**By [Christopher Muriithi Mwangi](https://www.linkedin.com/in/christopher-mwangi-894265b0)**  
📧 [nomiskris@gmail.com](mailto:nomiskris@gmail.com)  
💻 [@ChrisMuriithi](https://github.com/ChrisMuriithi)  
🎓 [Google Scholar](https://scholar.google.com/citations?user=isM9thcAAAAJ&hl=en)

