### 1. Introduction to Dataset

The dataset contains monthly financial transactions for **2023**, covering three business lines:

- Sports Equipment  
- Sportswear  
- Nutrition & Food Supplements  

Each record includes:

- **Revenue streams:** Sales, Consulting, Other Income  
- **Expense categories:** COGS, OPEX, Interest & Tax  
- **Time attributes:** Month, date, business line  
- **Financial amount:** Revenue or expense value  

The dataset allows full reconstruction of:

- Profit & Loss (P&L)  
- Gross Margin & Profit Margin  
- Cost allocation by category  
- Month-over-month trends  
- Break-even revenue  

### 2. Data Dictionary

| Field | Description |
|-------|-------------|
| **Year** | Financial year (2023) |
| **Month name / sequence** | Month label and numeric order |
| **Date** | End-of-month posting date |
| **Business Line** | Sports Equipment, Sportswear, Nutrition & Food Supplements |
| **Amount ($)** | Revenue or expense value |
| **Expense subgroup** | Rent, Payroll, Materials, Packaging, Shipping, Labor, etc. |
| **Revenue / Expense Group** | Sales, Consulting, Other Income, OPEX, COGS, Interest & Tax |
| **Revenue or Expense** | Classification of the transaction |

### 3. Business Questions

This dashboard answers key financial questions:

#### Revenue & Profitability
- What is total revenue, COGS, OPEX, EBIT, and Net Profit for the year?
- How do margins change month to month?

#### Cost Structure
- Which cost categories (Payroll, Marketing, Materials, Shipping) drive the most expenses?
- How does cost allocation differ across business lines?

#### Business Line Performance
- Which business line generates the highest revenue and profit?
- Which business line has negative profit margin?

## II. Design Thinking Method

### Step 1: Empathize
Finance teams need a single source of truth to monitor revenue, cost, and profitability. They require:
- Clear P&L structure  
- Cost allocation transparency  
- Business-line comparison  
- Monthly trend analysis  
- Break-even visibility  

### Step 2: Define
Core problem: The organization lacks a consolidated financial dashboard that integrates revenue, COGS, OPEX, and profitability across all business lines.

### Step 3: Ideate
Potential solutions:
- Executive Summary page with KPIs  
- Monthly revenue vs break-even chart  
- Cost allocation waterfall  
- Business-line profitability comparison  
- P&L table with drill-down  
- MoM trend charts for revenue, COGS, OPEX, EBIT  

### Step 4: Prototype
The first dashboard version includes:
- Executive Summary (Revenue, COGS, OPEX, EBIT, NP, margins)  
- Cost Analysis (Increase/Decrease waterfall)  
- Business Line Performance (Revenue + Profit Margin %)  
- Break-even Analysis  
- P&L Statement with detailed expense categories  

### Step 5: Review
Stakeholders validated:
- KPI definitions  
- Expense grouping logic  
- Margin calculations  
- Visual layout and readability  
- Business-line segmentation  

Final adjustments included:
- Standardizing color theme  
- Improving P&L table formatting  
- Adding MoM % indicators  

## III. Visualization

### 1. Finance Performance Analyst
<img width="2198" height="1745" alt="image" src="https://github.com/user-attachments/assets/6e2ef605-696b-4805-bbbb-f56dc9162093" />

### 2. Cost Analyst
<img width="2214" height="1658" alt="image" src="https://github.com/user-attachments/assets/65c96605-c81c-4922-8223-7655faaf7646" />

### 3. P&L
<img width="2149" height="1298" alt="image" src="https://github.com/user-attachments/assets/67236fcc-e4be-4f73-a945-1a46ea61523c" />


