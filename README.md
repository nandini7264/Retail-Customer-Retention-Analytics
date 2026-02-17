# 🏬 Retail Customer Retention Analytics – TARGET

---

## 📑 Table of Contents

- 📌 [Project Overview](#-project-overview)
- 🎯 [Project Objective](#-project-objective)
- 📂 [Dataset Description](#-dataset-description)
- 🧹 [Data Modeling & Cleaning](#-data-modeling--cleaning)
- 📉 [Churn & Retention Metrics](#-churn--retention-metrics)
- 🔁 [Repeat Purchase Analysis](#-repeat-purchase-analysis)
- 🎁 [Promotion & Loyalty Impact](#-promotion--loyalty-impact)
- 🏬 [Store & Channel Performance](#-store--channel-performance)
- 💰 [Customer Lifetime Value (CLV) Analysis](#-customer-lifetime-value-clv-analysis)
- 📊 [Final Dashboard Overview](#-final-dashboard-overview)
- 🛠 [Tools & Technologies Used](#-tools--technologies-used)
- 📁 [Project Structure](#-project-structure)
- 🚀 [Key Business Insights](#-key-business-insights)
- 🎯 [Strategic Recommendations](#-strategic-recommendations)
- 📌 [Conclusion](#-conclusion)

---

## 📌 Project Overview

Target Corporation operates across hypermarkets, discount stores, and e-commerce platforms.  
With increasing competition from major retail players, customer retention has become a strategic priority.

This project builds an interactive Customer Retention Analytics Dashboard in Power BI to analyze churn behavior, loyalty engagement, promotion effectiveness, and regional performance.

---

## 🎯 Project Objective

The goal of this project is to:

- Identify churn drivers and at-risk customers  
- Segment high-value and repeat customers  
- Evaluate loyalty tier effectiveness  
- Measure promotion and campaign impact  
- Provide actionable retention strategies  

---

## 📂 Dataset Description

The project integrates five structured datasets:

1. Customer_Demographics.csv  
2. Customer_Transactions.csv  
3. Store_Locations.csv  
4. Loyalty_Program.csv  
5. Churn_Labelled_Customers.csv  

These datasets collectively enable demographic analysis, transaction tracking, loyalty modeling, and churn evaluation.

---

## 🧹 Data Modeling & Cleaning

- Loaded and transformed datasets using Power Query  
- Handled duplicates and missing values  
- Standardized data types and date formats  
- Created calculated columns:
  - Membership Duration  
  - Transaction Year & Month  
- Built relational data model:
  - One-to-Many: Customers → Transactions, Loyalty, Churn  
  - Many-to-One: Transactions → Store Locations  

---

## 📉 Churn & Retention Metrics

- Calculated Churn Rate KPI:

  Churn Rate = (Churned Customers / Total Customers) × 100

- Analyzed churn by:
  - Region  
  - Income Level  
  - Preferred Channel  
  - Loyalty Tier  

- Designed retention funnel:
  Total Customers → Repeat Customers → Churned Customers  

---

## 🔁 Repeat Purchase Analysis

- Segmented customers:
  - Low-Tier (0–3 purchases)  
  - Mid-Tier (4–8 purchases)  
  - High-Tier (9+ purchases)  

- Compared average purchase frequency by:
  - Region  
  - Age Group  
  - Loyalty Tier  

- Identified most purchased categories among loyal customers  

---

## 🎁 Promotion & Loyalty Impact

- Calculated % of transactions with promotions  
- Compared average purchase amount:
  - With Promotion  
  - Without Promotion  

- Analyzed churn rate across loyalty tiers  
- Visualized Points Earned vs Points Redeemed  
- Assessed effectiveness of loyalty engagement strategies  

---

## 🏬 Store & Channel Performance

- Merged store data with transaction data  
- Evaluated:
  - Average transaction value by Store Type  
  - Churn rate by Store Type  
  - Correlation between Store Opening Year & Retention  

- Compared performance of:
  - Supercenters  
  - Neighborhood Markets  
  - Online  
  - Sam’s Club  

---

## 💰 Customer Lifetime Value (CLV) Analysis

CLV Formula:

CLV = Total Amount Spent / Membership Duration (Years)

- Segmented customers into:
  - High CLV (Above Average)  
  - Low CLV (Below Average)  

- Visualized:
  - CLV vs Days Since Last Purchase  
  - CLV by Loyalty Tier  
  - CLV by Region  

---

## 📊 Final Dashboard Overview

The Power BI report includes four interactive pages:

Page 1 – Executive KPIs  
- Churn Rate  
- CLV  
- Repeat Purchase Rate  

Page 2 – Loyalty & Promotion Impact  

Page 3 – Store & Channel Insights  

Page 4 – Customer Segmentation  

Interactive slicers:
- Region  
- Channel  
- Income Level  
- Loyalty Tier  

---

## 🛠 Tools & Technologies Used

- Power BI Desktop  
- Power Query (ETL)  
- Data Modeling  
- DAX Calculations  
- KPI Cards  
- Funnel Charts  
- Clustered Column Charts  
- Scatter Plots  
- Interactive Slicers  

---

## 📁 Project Structure

```bash
Retail-Customer-Retention-Analytics-Target/
│
├── Data/
│   ├── Customer_Demographics.csv
│   ├── Customer_Transactions.csv
│   ├── Store_Locations.csv
│   ├── Loyalty_Program.csv
│   └── Churn_Labelled_Customers.csv
│
├── Dashboard & Analysis/
│   └── Target Retention Study.pbix
│
├── Presentation/
│   └── Retail Customer Retention Analytics.docx
│
├── Screenshots/
│   ├── KPI_Dashboard.png
│   ├── Churn_Analysis.png
│   ├── Loyalty_Insights.png
│   └── CLV_Analysis.png
│
└── README.md
```

---

## 🚀 Key Business Insights

- Identified high churn segments by income and region  
- Determined loyalty tiers with strongest retention performance  
- Measured positive impact of promotions on transaction value  
- Identified high-CLV customers contributing majority revenue  
- Detected underperforming store formats affecting retention  

---

## 🎯 Strategic Recommendations

- Focus retention campaigns on mid-tier customers at risk of churn  
- Strengthen loyalty benefits for high-value segments  
- Reallocate marketing budget toward high-ROI regions  
- Optimize promotions based on historical uplift performance  
- Improve online channel engagement to reduce churn  

---

## 📌 Conclusion

This project delivers a comprehensive Customer Retention Intelligence Dashboard that integrates customer demographics, transactions, loyalty behavior, and churn data into a unified analytics solution.

It demonstrates:

- Strong data modeling capabilities  
- Advanced KPI computation  
- CLV and churn analysis  
- Business-driven insight generation  
- Executive-level dashboard design  

The final solution enables Target’s leadership to implement data-driven retention and loyalty optimization strategies.
