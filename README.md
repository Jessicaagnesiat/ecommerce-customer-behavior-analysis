# 🛒 Electronics E-Commerce Sales & Customer Behavior Analysis

![Python](https://img.shields.io/badge/Python-Pandas-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![EDA](https://img.shields.io/badge/Analysis-EDA-green)
![Customer%20Analytics](https://img.shields.io/badge/Customer-Analytics-orange)

## Project Overview

This project analyzes customer behavior and sales performance within an electronics e-commerce platform.

The objective is to identify key revenue drivers, evaluate customer retention, analyze customer purchasing behavior, and uncover opportunities to improve conversion, retention, and long term business growth.

The analysis was conducted using Python for data cleaning, preprocessing, and exploratory analysis, while Power BI was used to develop interactive dashboards for business monitoring and decision-making.

---
## Project Highlights

- 📈 Revenue grew by 26.79% despite a 27.72% decline in customers
- 🛒 Only 4.7% of product views converted into purchases
- 🔄 Repeat purchase rate remained low at 36%
- 🎯 20% of categories generated 84.21% of total revenue
- 👥 25.65% of customers were identified as churn risk users

---
## Business Problem

Between September 2020 and February 2021:

- Revenue increased by **26.79%**
- Customer base declined by **27.72%**
- Only **36% of customers** made repeat purchases
- Most users dropped off before completing a purchase

Although revenue growth appeared strong, underlying customer behavior indicated potential sustainability risks and weak long term retention. 

---

## Business Objectives

This project aims to answer the following business questions:

1. What drives revenue growth?
2. How strong is customer retention?
3. Where do customers drop off in the purchase funnel?
4. Is revenue concentrated within specific customer segments or product categories?
---

## Dataset

### Source

Kaggle – E-Commerce Events History in Electronics Store

### Dataset Information

- Period: September 2020 – February 2021
- 885,000+ user interaction records
- Customer journey:
  - View
  - Cart
  - Purchase

### Main Features

- event_time
- event_type
- product_id
- category_code
- brand
- price
- user_id
- user_session

---

## Tools & Technologies

- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- Power BI
- Jupyter Notebook

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Converted data types
- Removed 656 duplicate records
- Handled missing values
- Created additional features for analysis
- Saved cleaned data for dashboard development

---

# Key Findings

## 1. Revenue Growth Driven by Higher Customer Spending

Revenue increased by **26.79%** despite a **27.72% decline in customers**.

Further analysis revealed that revenue per customer increased by **75.43%**, indicating that growth was driven primarily by higher customer spending rather than customer acquisition.

---

## 2. Conversion Funnel Analysis

Customer funnel performance:

| Stage | Users |
|---------|---------|
| View | 793,099 |
| Cart | 54,032 |
| Purchase | 37,343 |

Only **4.7% of product views converted into purchases**, highlighting significant opportunities for conversion optimization.

Several products from the Electronics Telephone and Stationery Cartridge categories demonstrated the highest conversion rates.

---

## 3. Funnel Drop-Off Analysis
 
A deeper funnel analysis identified major friction points:

### View → Cart

Products with unclear categorization experienced the highest drop-off rates.

### Cart → Purchase

Higher-priced products (>$100) dominated cart abandonment behavior.

These findings suggest that product clarity, pricing strategy, and checkout experience significantly influence conversion performance.
---

## 4. Product Performance Analysis

Product ID **1821813** consistently ranked highest across:

- Product Views
- Add to Cart Actions
- Purchases

The Computer Components (Video Cards), CPU, and Electronics Telephone categories generated the strongest engagement throughout the customer journey.
---

## 5. Pareto Analysis

Approximately **20% of product categories generated 84.21% of total revenue**.

This strong Pareto distribution indicates that business performance depends heavily on a relatively small group of high-performing product categories.

Understanding these categories can help prioritize inventory management, marketing investments, and promotional campaigns.


---

## 6. Cohort Retention Analysis

Customer retention declined sharply after the first month.

Although repeat customers generated higher revenue than one time buyers, long term retention remained weak.

This indicates that the business relies heavily on short-term purchases rather than sustainable customer loyalty.

Repeat Purchase Rate:

**36%**

---

## 7. Customer Segmentation Analysis

Using customer behavior and transaction patterns, customers were segmented into:

| Segment | Revenue Contribution |
|----------|----------|
| Moderate Buyers | 47.64% |
| Churn Risk | 25.65% |
| Loyal but At Risk | 13.76% |
| High Value Customers | 11.39% |
| New Customers | Remaining Share |

A significant portion of customers were identified as churn risk users, highlighting opportunities for retention-focused campaigns.

---

# Business Recommendations

### Conversion Optimization

- Improve product descriptions and categorization
- Add high quality images and detailed specifications
- Display customer reviews and ratings
- Highlight product benefits more clearly

### Reduce Cart Abandonment

- Offer installment payment options
- Provide limited time discounts
- Introduce free shipping incentives
- Simplify checkout processes

### Customer Retention

- Create loyalty reward programs
- Launch personalized email campaigns
- Implement win back campaigns for churn risk customers
- Introduce VIP programs for high value customers

### Revenue Growth

- Prioritize high performing product categories
- Bundle complementary products
- Upsell premium product versions
- Improve inventory allocation for top selling items

---

# Dashboard Preview

## Business Performance Dashboard

![Business Performance Overview](Dashboard/Business%20Performance%20Overview.png)

## Product Performance Dashboard

![Product Performance](Dashboard/Product%20Performance.png)

## Customer Behaviour Dashboard

![Customer Behaviour](Dashboard/Customer%20Behaviour.png)

---

# Project Structure

```text
electronics-ecommerce-analysis
│
├── Dashboard
│   ├── Business Performance.png
│   ├── Product Performance.png
│   └── Customer Behaviour.png
│
├── Notebook
│   └── ecommerce_analysis.ipynb
│
├── Presentation
│   └── Electronics_Ecommerce_Sales_Analysis.pdf
│
└── README.md
```

---

# Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Conversion Funnel Analysis
- Funnel Drop Off Analysis
- Cohort Retention Analysis
- Pareto Analysis
- Customer Segmentation
- Customer Analytics
- Business Intelligence
- Power BI Dashboard Development
- Data Visualization
- Data Storytelling
- Business Recommendation Development

---

## Author

**Jessica Agnesia Tataung**

Aspiring Data Analyst | Python | SQL | Power BI | Tableau
