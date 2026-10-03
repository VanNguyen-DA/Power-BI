# Sales & Digital Marketing Performance Dashboard | Power BI

![Banneranner.png

**Author**: Nguyễn Thị Thanh Vân 

**Tool**: Power BI

## Table of Contents

- Background Overview
- Dataset Description
- Business Questions
- Design Thinking Process
- Key Insights & Visualizations
- Final Conclusions & Recommendations
- Tools Skills

---

# 📌 Background & Overview

## Project Objective

This project analyzes Marketing & Sales performance to help stakeholders monitor revenue, campaign effectiveness, customer behavior, product performance, and advertising efficiency.

## 👤 Who is this project for?

This dashboard is designed for:

- 📢 Marketing Managers to optimize campaign performance and ROAS
- 🛒 E-commerce Managers to monitor sales and product performance
- 📈 Sales Managers to track revenue growth and customer insights
- 🏢 Business Leaders to support data-driven decision-making

### Business Goals

- Optimize marketing spend
- Improve campaign performance
- Increase revenue growth
- Understand customer behavior
- Identify high-performing products
- Improve budget allocation decisions

## 🎯 Project Outcome

### Key Results

- Built an interactive Power BI dashboard to monitor sales, marketing, and customer performance.
- Identified top-performing campaigns, products, and customer segments.
- Improved budget allocation through ROAS and advertising efficiency analysis.
- Enabled faster, data-driven decision-making with automated reporting and KPI tracking.

---

# 📂 Dataset Description

### Dataset Includes

- Daily Revenue & Orders
- Advertising Spend
- Campaign Performance
- Product Performance
- Customer Segmentation
- Budget Tracking
- Geographic Analysis

### Data Dictionary

| Field | Description |
|---------|-------------|
| Date | Daily performance date |
| Campaign Name | Marketing campaign |
| Revenue | Total sales revenue |
| Ads Spend | Marketing spend |
| ROAS | Return on Ad Spend |
| CTR | Click-through rate |
| CPC | Cost per Click |
| Impressions | Ad impressions |
| Clicks | Total clicks |
| Orders | Number of orders |
| Customer Type | New / Returning |
| Membership Tier | Silver / Gold / Platinum / Diamond |
| City | Sales location |

---

# ❓ Business Questions

## Revenue & Ads Efficiency

- What is total revenue?
- How much revenue is driven by paid ads?
- Which periods have low ROAS?
- Is advertising spend profitable?

## Customer Insights

- New vs Returning customer ratio?
- Which membership tier generates the highest revenue?

## Campaign Performance

- Top campaigns by revenue?
- Top campaigns by ROAS?
- Which campaigns exceed budget?

## Product Performance

- Top product categories by revenue?
- Most cost-efficient products?
- Highest converting products?

## Geographic Analysis

- Which cities generate the most revenue?
- Which cities deserve more marketing budget?

---

# 🧠 Design Thinking Process

## Stage 1: Empathize

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b012c56b-c37c-4077-b996-d3790ca6338a" />

## Stage 2: Define

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/a366dbd4-2b08-48c2-acc7-42f15d8a9633" />

## Stage 3: Ideate

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/913d7bda-b2f1-4058-8c37-28f72b4b21e8" />

---

# 🏗️ Data Model

## Data Relationships

<img width="1097" height="467" alt="image" src="https://github.com/user-attachments/assets/53ff311e-ee4f-46b3-bd46-d56be3f985b6" />

### Fact Tables

- Fact Order
- Fact Marketing Campaign by SKU Cost

### Dimension Tables

- Date
- Product (Danh Sach San Pham)
- Marketing Campaign Cost

---

# 📊 Dashboard Pages

## 1️⃣ Overview Dashboard

### KPI Cards

- Revenue
- Orders
- Ads Spend
- ROAS
- Budget Usage

<img width="2662" height="1799" alt="image" src="https://github.com/user-attachments/assets/d45c648c-669a-4969-9efc-5a2db72213e9" />


---

## 2️⃣ Sales & Customer Dashboard

### Analysis Includes

- Revenue Trend
- Customer Segmentation
- Membership Analysis
- Revenue by City

<img width="2161" height="1798" alt="image" src="https://github.com/user-attachments/assets/e229f7bd-c8ee-4b80-8984-d8d3dd5bca50" />


---

## 3️⃣ Campaign Performance Dashboard

### Metrics

- Impressions
- Clicks
- CTR
- CPC
- CPM
- ROAS
- Budget Utilization

<img width="2658" height="1793" alt="image" src="https://github.com/user-attachments/assets/b7a15ede-1a21-475e-8523-85268166dd41" />


---

## 4️⃣ Product Performance Dashboard

### Metrics

- Revenue by Category
- Orders by Product
- Product ROAS
- Cost Efficiency

<img width="2488" height="1800" alt="image" src="https://github.com/user-attachments/assets/388bbc93-32af-4729-8968-940e6233aa14" />

---

# 💡 Key Insights

- Generated **5bn revenue** with **394M ad spend**, achieving a strong **ROAS of 7.67**.
- **63% of total revenue (3bn)** comes from advertising channels, showing high dependence on paid marketing.
- Existing customers (**6.93K**) significantly outnumber new customers (**3.09K**), indicating strong retention.
- Top-performing categories are **Váy Chiết Eo Xòe**, **Áo Tách Set**, and **Set Váy Áo**.
- **Váy Chiết Eo Ôm** delivers the highest efficiency with **ROAS 22** and **77% order rate**.
- Marketing generated **5.11M impressions** and **41.65K clicks**, but **CTR remains low at 1%**.
- The **Audrey Shirt** product line leads in impressions, clicks, and customer interactions.


# 📋 Final Conclusions & Recommendations

| Aspect | Insight | Recommendation |
|----------|----------|----------|
| Overall Performance | The business generated **5bn revenue** with a strong **ROAS of 7.67**, indicating effective marketing performance. | Continue scaling profitable campaigns while maintaining ROAS efficiency. |
| Revenue Source | **63% of total revenue** comes from advertising channels, showing high dependence on paid marketing. | Diversify revenue sources by strengthening direct and organic sales channels. |
| Customer Base | Existing customers (**6.93K**) significantly outnumber new customers (**3.09K**), demonstrating strong retention. | Increase customer acquisition through referral programs, promotions, and targeted campaigns. |
| Product Performance | Revenue is concentrated in a few categories, led by **Váy Chiết Eo Xòe**, **Áo Tách Set**, and **Set Váy Áo**. | Expand promotion of mid-performing products to reduce dependency on top categories. |
| Campaign Efficiency | **Váy Chiết Eo Ôm** achieves the highest **ROAS (22)** and **Order Rate (77%)**. | Allocate more marketing budget to high-performing categories and products. |
| Marketing Engagement | Despite **5.11M impressions**, CTR remains low at **1%**. | Improve ad creatives, targeting, and call-to-action messaging to increase engagement. |
| Campaign Portfolio | A small number of campaigns and products generate most of the results. | Reallocate budget from low-performing campaigns to top-performing campaigns such as the Audrey Shirt series. |
| Growth Opportunity | Budget utilization remains below the total allocated budget. | Invest the remaining budget in proven high-ROAS products and customer acquisition initiatives. |

## ✅ Final Conclusion
The business demonstrates strong profitability with **5bn revenue** and **ROAS of 7.67**. Future growth should focus on scaling high-performing products and campaigns, improving ad engagement, attracting new customers, and reducing reliance on a small number of products and advertising-driven sales.



