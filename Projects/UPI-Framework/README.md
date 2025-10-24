# UPI Framework Implementation Project: Advancing Client Registry and Interoperability at EDARP  

*Digitally transforming patient identity management through a unified, verifiable, and interoperable client registry system aligned with Kenya’s national health digital strategy.*

---

## 🧩 Project Overview
The **Unique Patient Identifier (UPI) Framework Implementation Project** was launched by **Eastern Deanery AIDS Relief Program (EDARP)** to align with the **Kenya Health Act (2017)** and the **Ministry of Health’s UPI Technical Framework**.  

The initiative established a **client registry** that ensures each patient has a **single, verifiable, and interoperable identifier** across EDARP’s 14 facilities. It enhances **data accuracy**, **continuity of care**, and **interoperability** between EDARP’s **Ecare EMR**, community data systems, and national digital health platforms such as **DHIS2**, **NiShauri**, and **Ushauri**.

As the **Project Lead and M&E/ICT Manager**, I led the system design, data mapping, and **API-based integration** of facility EMRs with external registries, embedding strong **data protection and consent management workflows** throughout.

---

## 🎯 Core Objectives
- Operationalize a **nationally compliant UPI generation and verification framework**  
- Enable **data exchange** between EDARP’s EMR and national health information systems  
- Reduce **duplicate records** and improve client tracking and data quality  
- Embed **data protection**, audit trails, and **informed consent processes** into EMR workflows  

---

## 🧰 Languages & Utilities Used
| Tool / Platform | Purpose |
|------------------|----------|
| **SQL Server** | Core client registry, record linkage, and data validation |
| **Python** | Record deduplication and matching using Levenshtein and fuzzy logic |
| **RESTful APIs (JSON)** | Data exchange between EMR, NiShauri, and Ushauri |
| **Postman** | API testing, endpoint documentation, and sandbox validation |
| **Excel / Power Query** | UPI validation checks and interim data reconciliation |
| **NVivo** | Qualitative analysis of pilot testing feedback from facilities |
| **Power BI** | Dashboards visualizing UPI coverage, verification, and duplicates resolved |

---

## 🖥️ Environment / Platforms Used
- **Ecare EMR** with integrated UPI registry module  
- **Microsoft SQL Server** for backend database operations and stored procedures  
- **MoH UPI API Sandbox (FHIR-compliant)** for interoperability testing  
- **Power BI Service** for live tracking of verification and deduplication metrics  
- **Secure Cloud Backup** with nightly encrypted synchronization  

---

## 🧭 Implementation Walkthrough

### 1. Requirement Analysis  
Conducted system audits across **14 EDARP clinics** to identify duplicate patient records and identification gaps.  
Reviewed **Kenya’s UPI Framework** to ensure compliance with national standards.

### 2. UPI Generation and Structure Design  
Adopted **National ID** and **Birth Certificate** numbers as primary data sources.  
Designed fallback logic for clients without formal IDs using community-level identifiers.

### 3. System Integration  
Developed **SQL procedures** to generate and validate UPIs automatically within EMR.  
Implemented **RESTful APIs** for real-time record verification with **NiShauri** and **Ushauri**.  
Added **consent capture** and **audit trail tracking** for full **DPA 2019** compliance.

### 4. Data Cleaning and Verification  
Used **Python scripts** for record matching (Levenshtein distance, fuzzy matching) to identify and merge duplicates.  
Created **SQL reconciliation scripts** for periodic verification and completeness checks.

### 5. Dashboard and Monitoring  
Designed a **Power BI dashboard** visualizing facility-level UPI coverage, duplicates resolved, and verification success rates.  
Enabled **automated weekly refreshes** for real-time performance tracking.

### 6. Capacity Building and Rollout  
Trained **28 data officers and facility leads** on UPI workflows, data protection, and troubleshooting.  
Piloted the system in **3 facilities** before scaling to all 14.

---

## 📦 Key Outputs / Deliverables
- ✅ **Ecare EMR UPI Module** for automated identifier generation and validation  
- ✅ **UPI Coverage Dashboard** visualizing registration and verification performance  
- ✅ **SQL/Python Reconciliation Scripts** for deduplication and record matching  
- ✅ **UPI Integration Manual** documenting EMR–NiShauri–Ushauri API connections  
- ✅ **Training Package** for staff capacity-building and data protection awareness  

---

## 📈 Results & Impact
| Outcome | Result |
|----------|---------|
| **Duplicate Reduction** | Reduced duplicate patient records by **67%** across all facilities |
| **Interoperability** | Exchanged over **40,000 client records** with external systems |
| **Data Quality** | Improved UPI coverage from **54% → 95%** within six months |
| **Efficiency Gains** | Enabled **instant patient verification** at point of service |
| **Data Protection Compliance** | Embedded **consent and audit trails** across all registry workflows |

---

## 💡 Lessons Learned & Future Improvements
- **Challenge:** Some clients lacked formal IDs, limiting full verification coverage.  
- **Solution:** Introduced **temporary identifiers** linked to EMR-generated UPI logic.  
- **Next Steps:**  
  - Introduce **biometric validation** for higher accuracy  
  - Apply **machine learning** for duplicate detection and anomaly scoring  
  - Integrate UPI data with **NHIF/SHIF** for universal coverage tracking  

---

## 📂 Visuals and Documentation
Suggested repository folder structure:


---

## 🏷️ Tags / Keywords
`#UPI` `#DigitalHealth` `#Interoperability` `#DataGovernance` `#EMR` `#APIs`  
`#PowerBI` `#SQLServer` `#KenyaHealthAct2017` `#DataProtectionAct2019` `#EDARP`  

---

## 🧾 Badges
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![API](https://img.shields.io/badge/RESTful%20APIs-000000?style=for-the-badge&logo=api&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![NVivo](https://img.shields.io/badge/NVivo-005B96?style=for-the-badge)
![Kenya](https://img.shields.io/badge/Kenya-006600?style=for-the-badge&logo=googleearth&logoColor=white)
![EDARP](https://img.shields.io/badge/EDARP-003399?style=for-the-badge)

---

## 👤 Author
**By [Christopher Muriithi Mwangi](https://www.linkedin.com/in/christopher-mwangi-894265b0)**  
📧 [nomiskris@gmail.com](mailto:nomiskris@gmail.com)  
💻 [@ChrisMuriithi](https://github.com/ChrisMuriithi)  
🎓 [Google Scholar](https://scholar.google.com/citations?user=isM9thcAAAAJ&hl=en)

