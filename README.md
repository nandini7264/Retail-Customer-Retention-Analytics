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

- Performed data transformation in Power Query including handling missing values, removing duplicates, and standardizing data types.
- Built relational data model connecting customers, transactions, loyalty, churn, and store tables.
- Created calculated columns for membership duration and time-based transaction analysis.

---

## 📉 Churn & Retention Metrics

- Calculated overall churn rate and segmented churn by region, income level, channel, and loyalty tier.
- Designed a customer funnel to analyze movement from total customers to repeat and churned segments.
- Identified high-risk customer groups contributing most to churn.

---

## 🔁 Repeat Purchase Analysis

- Segmented customers based on purchase frequency to identify low, mid, and high-value repeat buyers.
- Compared repeat behavior across regions, age groups, and loyalty tiers.
- Determined product categories most preferred by loyal customers.

---

## 🎁 Promotion & Loyalty Impact

- Analyzed transaction data to measure the impact of promotions on average purchase value.
- Evaluated loyalty tier performance using churn comparison and redemption behavior.
- Assessed how engagement through loyalty points influenced retention.

---

## 🏬 Store & Channel Performance

- Merged transaction and store data to evaluate performance across store formats and online channels.
- Compared churn and average transaction value by store type.
- Analyzed relationship between store maturity and customer retention trends.

---

## 💰 Customer Lifetime Value (CLV) Analysis

- Calculated CLV using total spend and membership duration.
- Segmented customers into high and low CLV groups for strategic targeting.
- Analyzed CLV distribution across loyalty tiers and regions to identify revenue-driving segments.

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
