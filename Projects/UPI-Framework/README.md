# **UPI Framework Implementation Project: Advancing Client Registry and Interoperability at EDARP**

## 1. Description
Aligned with the Kenya Health Act (2017), this project operationalized a **Unique Patient Identifier (UPI)** across 14 facilities to improve data accuracy and interoperability (Ecare EMR ↔ NiShauri/Ushauri/DHIS2). I led system design, data mapping, and API integration with embedded consent management.

## 2. Languages and Utilities Used
SQL Server; Python; REST/JSON; Postman; Excel/Power Query; NVivo; Power BI.

## 3. Environment / Platforms Used
Ecare EMR v4.2; SQL Server 2019; MoH UPI API Sandbox (FHIR-compliant); Power BI Service; encrypted cloud backup.

## 4. Step-by-Step Walkthrough
Requirements audit → UPI generation logic (NatID/Birth Cert with fallbacks) → SQL procedures + APIs to external platforms → fuzzy-match deduping → UPI coverage dashboard → training & phased rollout.

## 5. Key Outputs / Deliverables
EMR UPI module; coverage dashboard; reconciliation scripts; integration manual; training package.

## 6. Results and Impact
Duplicates −67%; 40k+ records exchanged; UPI coverage 54%→95% in 6 months; instant ID verification and audit trails.

## 7. Lessons Learned / Future Improvements
Temporary IDs for undocumented clients; next: biometrics, ML duplicate detection, SHIF linkage.

## 9. Tags / Keywords
`#UPI` `#Interoperability` `#DataGovernance` `#PowerBI` `#SQLServer` `#Kenya`
