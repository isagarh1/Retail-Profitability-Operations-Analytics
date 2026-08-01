# Retail Profit Leakage & Operational Analytics

##  Project Overview

Retail businesses often generate strong sales but still struggle to maximize profitability due to pricing, discounting, returns, and operational inefficiencies.

This project analyzes retail sales performance to identify the key drivers of profit leakage using **PostgreSQL** and **Power BI**. The analysis combines business-focused SQL, interactive dashboards, and Root Cause Analysis (RCA) to uncover profitability issues and provide actionable business recommendations.

--- 

##  Key Business Metrics

| Metric | Value |
|--------|------:|
| Total Sales | $2.30M |
| Total Profit | $286.4K |
| Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Return Rate | 8.0% |
| Avg. Fulfillment Days | 34.6 Days |

---

##  Business Problem

Despite generating strong revenue, businesses can still experience declining profitability due to ineffective pricing strategies, excessive discounting, operational inefficiencies, and low-performing products.

The objective of this project is to identify where profit leakage occurs, understand the underlying business drivers, and provide data-driven recommendations to improve profitability.

---

##  Business Objectives

- Analyze sales, profit, and profit margins across regions and product categories.
- Identify products, customers, and regions contributing to profit leakage.
- Evaluate the impact of discounts, returns, and fulfillment efficiency on profitability.
- Perform Root Cause Analysis (RCA) to identify key profitability drivers.
- Develop interactive dashboards and provide actionable business recommendations.

---

## Dataset Information

| Attribute | Details |
|-----------|---------|
| Domain | Retail Analytics |
| Records | 9,994 |
| Columns | 22 |
| Granularity | Order-Level Transactions |
| Tools Used | PostgreSQL, Power BI, Microsoft Excel |

### Dataset Features

- Customer & Order Information
- Product Category & Sub-Category
- Sales, Profit & Discount
- Shipping & Fulfillment Details
- Regional & Geographic Information
---

##  Analytical Approach

- Explored and validated retail order-level data.
- Performed exploratory and business-focused analysis using PostgreSQL.
- Calculated KPIs using CTEs, Window Functions, CASE expressions, Ranking, and Time-Series Analysis.
- Built interactive Power BI dashboards for executive reporting and operational insights.
- Conducted Root Cause Analysis (RCA) and developed strategic business recommendations.

---

## 📊 Dashboard Overview

Executive Overview
[<img width="1280" height="721" alt="Overview" src="https://github.com/user-attachments/assets/1d023f52-ca86-44b7-8b1f-8a5098fa9c31" />
]

Profit Leakage & Operational Analytics
[<img width="1282" height="710" alt="Profit leakage" src="https://github.com/user-attachments/assets/6d02348a-f5b4-43ab-b75c-45b499d0f978" />
]

Profit Leakage Investigation (RCA)
[<img width="1272" height="707" alt="Investigation" src="https://github.com/user-attachments/assets/f38660c5-e2e1-46b4-bce2-b4575330bc94" />
]


---

##  Key Findings

- Furniture recorded the lowest profit margin (**2.49%**), significantly underperforming other product categories.
- Tables emerged as the primary source of profit leakage, generating negative profit across multiple regions.
- Average discounts exceeding **20%** were associated with loss-making Furniture products.
- Profitability varied across regions, demonstrating that higher sales did not always translate into higher profit.
- Stable return rates indicated that returns were not the primary driver of profit leakage.

---

##  Root Cause Analysis

A detailed Root Cause Analysis (RCA) was performed to investigate the factors contributing to profit leakage. The analysis revealed that margin erosion was primarily driven by low-performing Furniture sub-categories, particularly **Tables**, where higher discount levels coincided with negative profitability across multiple regions. Additional investigation showed that return rates remained relatively stable, indicating that pricing strategy rather than returns was the primary contributor to profit leakage.

---

##  Business Impact

- Identified low-margin products requiring immediate pricing review.
- Highlighted opportunities to improve profitability through optimized discount strategies.
- Demonstrated the importance of monitoring profitability alongside revenue.
- Provided decision-makers with actionable insights to support sustainable business growth.

---

##  Strategic Recommendations

- **Optimize Pricing & Discount Strategy:** Review discounts for low-margin Furniture products and introduce margin-based approval thresholds.
- **Strengthen Profitability Monitoring:** Continuously monitor product profitability, discount levels, and regional performance to identify margin erosion early.
- **Adopt Profit-Focused Decision Making:** Incorporate profitability metrics into pricing, promotional campaigns, and sales performance evaluations.

---

## 🛠️ Skills Demonstrated

- SQL (PostgreSQL)
- Power BI
- Data Cleaning & Validation
- Exploratory Data Analysis (EDA)
- KPI Development
- Business Analysis
- Root Cause Analysis (RCA)
- Dashboard Design
- Data Visualization
- Business Storytelling

---

##  Business Value Delivered

This project demonstrates how data analytics can move beyond descriptive reporting by identifying the underlying drivers of profit leakage and translating analytical findings into actionable business recommendations. The dashboards support stakeholders in monitoring profitability, prioritizing pricing decisions, and improving overall business performance.


---

## Author

**Sagar Hiware**

LinkedIn: https://linkedin.com/in/isagarhiware1
GitHub: https://github.com/isagarh1
