# FUTURE_DS_02: Customer Retention & Churn Analysis

## Project Overview
This project focuses on calculating and analyzing key business performance metrics—**Customer Retention Rate** and **Churn Rate**—over a 6-month period (January to June). By tracking these trends, businesses can determine user loyalty, pinpoint where customer loss peaks, and implement data-driven strategies to improve customer lifetime value.

---

##  Executive Dashboard Visuals
Below are the dynamic visual charts tracking our customer retention and churn trends side-by-side:

![Dashboard Preview](Screenshot%202026-05-27%20003401.png)

---

##  Calculated Performance Metrics
The data table below was built dynamically in Excel using automated logic formulas:
* **Retention Rate Formula:** `=((Ending Customers - New Customers) / Starting Customers)`
* **Churn Rate Formula:** `=1 - Retention Rate`

| Month | Starting Customers | New Customers Acquired | Ending Customers | Retention Rate (%) | Churn Rate (%) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **January** | 1,000 | 150 | 1,050 | **90%** | **10%** |
| **February** | 1,050 | 160 | 1,110 | **90%** | **10%** |
| **March** | 1,110 | 130 | 1,140 | **91%** | **9%** |
| **April** | 1,140 | 180 | 1,200 | **89%** | **11%** |
| **May** | 1,200 | 200 | 1,270 | **89%** | **11%** |
| **June** | 1,270 | 220 | 1,340 | **88%** | **12%** |

---

##  Key Insights & Business Observations
1. **The Peak (March):** March achieved our highest retention rate (**91%**) and lowest customer churn (**9%**). This indicates strong user engagement and successful service satisfaction during this period.
2. **The Trend Downward (April - June):** Starting in April, retention dropped to **89%** and hit a low of **88%** by June. Concurrently, churn grew to **12%**. This indicates a steady upward trend in customer loss that requires immediate business attention.
3. **Core Recommendation:** The business needs to investigate why customer drop-off accelerated across Q2 (April to June) and introduce customer loyalty programs or engagement campaigns to curb the climbing churn rate.

---

## 📁 Repository Contents
* 📊 `task_2_retention_analysis.xlsx`: Complete interactive workbook containing formulas, structured calculations, and the main dashboard sheet.
* 🖼️ `Screenshot 2026-05-27 003401.png`: Visual dashboard image layout showing the trend charts side-by-side.
