# 📊 Telecom Customer Churn Analysis

🔗 🌐 **Open Project in Your Browser**: https://arrao10.github.io/Telecom-Customer-Churn-Analysis/

---

### 📖 Introduction
**Customer Churn** is one of the most critical business metrics in the telecom industry, directly impacting revenue and long-term growth. This project analyzes churn behavior across **California telecom customers in Q2 2022** using **Power BI**, uncovering the key drivers behind customer attrition and quantifying its financial impact across demographics, services, offers, and billing patterns.

---

### 🎯 Problem Statement
To build an end-to-end interactive Power BI dashboard that identifies why customers churn, which segments are most at risk, and how much revenue is being lost — enabling data-driven retention strategies.

---

### 🌟 Impact
The analysis reveals actionable churn patterns across customer demographics, service usage, contract types, and geographic regions, helping telecom businesses prioritize high-value retention efforts.

---

### 📂 Dataset Details
- **Source**: Maven Analytics Telecom Customer Churn Dataset
- **Total Customers**: **7,043** · **Location**: California · **Period**: Q2 2022
- **Original Format**: Flat CSV with **38 columns**
- **Data Model**: Split into **10 tables** via Power Query → Star schema with 1:1 and many-to-one relationships

---

### 📊 Reports
| # | Report | Description |
|---|--------|-------------|
| Report1 | Churn Drivers & Financial Impact | Primary churn categories, revenue lost, high-value churned customers |
| Report2 | Demographic Influences | Age group, marital status, gender — with Sunburst chart |
| Report3 | Offer Effectiveness & Referral Behavior | Which offers retain customers, referral patterns |
| Report4 | Service Relationships to Churn | Internet type, streaming, add-ons — with Sankey chart |
| Report5 | Geographic & Billing Patterns | City-level churn map, charge risk bands, refund ratios |
| Additional Information | Documentation | DAX functions, AppSource visuals, data model explanation |

---

### 🧮 Key DAX Measures
`Churn Rate %` · `Revenue Lost to Churn` · `Avg Revenue Per Customer` · `Churn Risk Score` · `Revenue At Risk` · `High Value Churned` · `Avg Services Per Customer` · `% Churned Revenue of Selected Internet Types` *(ALLSELECTED)* · `Charge to Refund Ratio` · `Churned Revenue %` · `Extra Charges Per Customer`

---

### 🛠️ Tools & Techniques
- **Power BI Desktop** — Report building, data modeling, DAX
- **Power Query** — Data cleaning, table splitting, unpivoting, reference queries
- **DAX** — `CALCULATE`, `AVERAGEX`, `DIVIDE`, `VAR/RETURN`, `HASONEFILTER`, `ALLSELECTED`, `FILTER`
- **AppSource Visuals** — Sunburst Chart, Sankey Chart (both by Microsoft)
- **Data Modeling** — 10-table star schema, 1:1 and many-to-one relationships
