# Business Analysis: EPI vs Minimum Premium Variances  

## 📌 Project Overview  
This project focuses on a reconciliation analysis between **Estimated Premium Income (EPI)** and **Minimum Premium (MINPREM)** datasets. The goal was to assess consistency across systems, evaluate the scale and distribution of variances, and uncover insights into the root causes of discrepancies.  

The project demonstrates skills in:  
- Business & financial data analysis  
- Variance analysis and reconciliation  
- Data visualization & dashboarding  
- Insights generation and recommendation reporting  

---

## 📊 Dataset  
<img width="1920" height="1080" alt="Screenshot 2025-09-19 025525" src="https://github.com/user-attachments/assets/1093505f-2320-4a07-9793-f7e8f1bd97a1" />

- **Source:** Reconciliation spreadsheets provided for EPI and MINPREM  
- **Volume:** 181 records across multiple Business IDs and years  
- **Scope:** Comparative analysis between EPI-only variances and combined EPI & MINPREM variances  

---

## 🔎 Key Findings  
- **EPI Variances:** Small, stable, and clustered close to zero (~137.8M total variance; max deviation 13.7M).  
- **MINPREM Variances:** Significantly larger and systemic (~-1.59B total variance; max deviation 63.1M).  
- **Primary Contributors:** Specific years (2013, 2008, 2007) and selected Business IDs account for the bulk of reconciliation issues.  
- **Risk Insight:** MINPREM dominates >90% of mismatches, suggesting structural rather than random issues.  

---

## 📈 Visualizations & Dashboard  
<img width="1221" height="781" alt="dashboard" src="https://github.com/user-attachments/assets/a2788d48-159a-4d5e-b25b-b015088072b9" />

The analysis is supported by visual dashboards, including:  
- **Line Chart:** Trends of variances over time (showing EPI stability vs MINPREM volatility).  
- **Correlation Chart:** Relationship between EPI and MINPREM variances.  
- **Top 10 Variance Analysis:** Highlighting the largest discrepancies by year and Business ID.  

---

## ✅ Conclusion  
Discrepancies are primarily driven by **MINPREM**, with recurring systemic issues linked to certain years and Business IDs. In contrast, EPI remains consistent and low-risk for reconciliation. These findings highlight material risks to financial reporting if MINPREM processes are not corrected.  

---

## 💡 Recommendations  
- **Targeted Root Cause Analysis** on high-variance years and Business IDs.  
- **System Review & Reconfiguration** for MINPREM calculation and data flow.  
- **Enhanced Data Controls & Alerts** for real-time variance detection.  
- **Governance & Automation** with reconciliation dashboards and automated checks.  

---

## 📂 Repository Contents  
- **/data** → Raw and processed reconciliation data (sample or anonymized).  
- **/analysis** → Excel workbooks with pivot tables, calculations, and summaries.  
- **/dashboard** → Visualizations (charts, top-variance plots, trends).  
- **Report.pdf** → Full business analysis report with annexed dashboards.  

---

## 🚀 Skills Demonstrated  
- Data Cleaning & Transformation (Excel, Pivot Tables)  
- Exploratory & Variance Analysis  
- Business Intelligence & Dashboarding  
- Business Reporting & Recommendations  
