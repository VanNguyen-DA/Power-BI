# Sales & Digital Marketing Performance Dashboard | Power BI

![Banneranner.png

**Author**: Nguyễn Thị Thanh Vân
**Tool**: Power BI

## Table of Contents

- background overview
- #-dataset-description
- [-business-questions
- #-design-thinking-process
- [-data-model
- #-dashboard-pages
- [-key-insights
- #-recommendations
- #-tools--skills

---

# 📌 Background & Overview

## Project Objective

This project analyzes sales and digital marketing performance to help stakeholders monitor revenue, campaign effectiveness, customer behavior, product performance, and advertising efficiency.

### Business Goals

- Optimize marketing spend
- Improve campaign performance
- Increase revenue growth
- Understand customer behavior
- Identify high-performing products
- Improve budget allocation decisions

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

## 1️⃣ Empathize

Stakeholders need a centralized dashboard to monitor sales and marketing performance in real time.

## 2️⃣ Define

### Problem Statement

Marketing teams lack a unified solution to evaluate campaign performance, customer behavior, and budget effectiveness.

## 3️⃣ Ideate

Proposed solutions:

- Executive Dashboard
- Campaign Analytics
- Customer Segmentation
- Product Performance Analysis
- Budget Monitoring
- Geographic Sales Analysis

## 4️⃣ Prototype

Dashboard consists of:

- Overview
- Sales & Customers
- Campaign Performance
- Product Performance
- Recommendations

## 5️⃣ Review

Validated with stakeholders:

- KPI Definitions
- Visual Consistency
- Dashboard Usability
- Marketing Metrics Accuracy

---

# 🏗️ Data Model

## Star Schema

images/data_model.png

### Fact Tables

- Sales Fact
- Marketing Fact

### Dimension Tables

- Date
- Product
- Campaign
- Customer
- Geography

---

# 📊 Dashboard Pages

## 1️⃣ Overview Dashboard

### KPI Cards

- Revenue
- Orders
- Ads Spend
- ROAS
- Budget Usage

images/overview.png

---

## 2️⃣ Sales & Customer Dashboard

### Analysis Includes

- Revenue Trend
- Customer Segmentation
- Membership Analysis
- Revenue by City

images/customer.png

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

images/campaign.png

---

## 4️⃣ Product Performance Dashboard

### Metrics

- Revenue by Category
- Orders by Product
- Product ROAS
- Cost Efficiency

images/product.png

---

# 💡 Key Insights

### Revenue

- Paid campaigns generated the majority of revenue growth.
- Revenue showed strong correlation with ad spend investment.

### Customer

- Returning customers contributed significantly higher revenue.
- Gold and Platinum members generated the highest purchase value.

### Campaign

- Several campaigns exceeded budget while producing below-average ROAS.
- Top-performing campaigns generated disproportionately high sales.

### Product

- Revenue concentrated within a limited number of categories.
- High-impression products did not always generate high sales.

### Geography

- Major cities contributed most revenue.
- Emerging cities showed strong growth potential.

---

# 🚀 Recommendations

✅ Increase budget for high-ROAS campaigns

✅ Reduce spend on low-converting campaigns

✅ Focus retention programs on repeat customers

✅ Scale investment in top-performing product categories

✅ Prioritize marketing efforts in high-growth cities

---

# 🛠️ Tools & Skills

### Tools

- Power BI
- Power Query
- DAX
- Excel

### Skills Demonstrated

- Marketing Analytics
- Sales Analytics
- Business Intelligence
- Dashboard Design
- Data Modeling
- DAX Calculations
- Customer Segmentation
- Marketing Performance Analysis
- Data Storytelling
