# Retail-Profitability-PowerBI
Power BI Project: Retail Profitability &amp; Discount Sensitivity Analytics
# 📊 Retail Profitability & Sales Performance Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-Desktop_%26_DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Download Case Study](https://img.shields.io/badge/Case_Study-PDF_Report-E04E39?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white)](./Retail_Profitability_Case_Study.pdf)
[![Download PBIX](https://img.shields.io/badge/Download_Model-.PBIX_File-2BAF2B?style=for-the-badge&logo=github&logoColor=white)](./PowerBI_final_Project.pbix)

---

## 🎯 Executive Summary & Business Problem
In retail and omnichannel sales operations, driving top-line revenue without granular control over discount dynamics often deteriorates the overall operating margin. 

This Business Data Analytics project delivers an end-to-end Power BI reporting solution that connects transactional sales data, regional distribution metrics, and product hierarchies to answer critical managerial questions:
- What is the net impact of variable discount tiers on regional gross margins?
- Which product segments and SKU categories act as margin drivers versus margin drainers?
- Where should executive management reallocate commercial resources to maximize overall profitability?

---

## 📑 In-Depth Business Case Study
A comprehensive business analysis report with root-cause breakdowns, strategic takeaways, and actionable recommendations is documented in the dedicated case study:

👉 **[Download the Full Case Study (PDF)](./Retail_Profitability_Case_Study.pdf)**

---

## 🖥️ Dashboard Interactive Previews

### 1. Executive Performance & Sales Analysis Overview
*High-level overview covering total revenue, gross margin, regional distributions, and core KPI scorecards.*

![Dashboard Overview](./PowerBI_final_Project_page1.png)

---

### 2. Profitability, Margin Drivers & Discount Analytics
*Detailed diagnostic view evaluating discount elasticities, segment-level profitability, and unit margins.*

![Profitability Analytics](./PowerBI_final_Project_page2.png)

---

## 🔍 Key Insights & Analytical Findings
1. **Discount Sensitivity vs. Margin Compression:**  
   Aggressive promotional discounts exceeding predefined thresholds directly erode net margins without delivering proportionate unit volume elasticity.
2. **Channel & Regional Dispersion:**  
   Specific geographical clusters generate high gross transaction volume (GTV) but underperform on operating profit due to fulfillment and pricing inefficiencies.
3. **Product Mix Optimization:**  
   A concentrated subset of high-margin product families accounts for the majority of net contribution margin, highlighting clear opportunities for portfolio rationalization.

---

## 🛠️ Data Model, Architecture & DAX Highlights
- **Schema Design:** Star Schema with clean Fact-Dimension relationships (`Fact_Sales`, `Dim_Date`, `Dim_Product`, `Dim_Geography`).
- **Data Transformation (Power Query):** Normalized schemas, removed transactional redundancies, and enforced typed data structures.
- **Analytical Measures (DAX):**
  - Robust Time-Intelligence metrics (`YTD`, `YoY Growth`, `Moving Averages`).
  - Dynamic Profit Margin calculation accounting for dynamic discounts and operational costs.
  - Variance and contribution analyses across categorical hierarchies.

---

## 📥 How to Access and Run the Dashboard
1. **Clone or Download the Repository:**
```bash
   git clone https://github.com/<YOUR_GITHUB_USERNAME>/<YOUR_REPOSITORY_NAME>.git
   
