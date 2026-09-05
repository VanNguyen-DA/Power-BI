## I. Introduction

### 1. Introduction to Dataset

This project uses a comprehensive HR dataset containing 298 employees with detailed attributes such as:

- **Demographics:** age, gender, race, citizenship  
- **Employment details:** department, position, manager, hire date  
- **Performance & satisfaction scores**  
- **Salary & absence records**  
- **Termination reasons and retention risk**  
- **Recruitment sources**

### 2. Data Dictionary

A summarized dictionary of the main fields:

- **EmployeeID** — Unique identifier for each employee  
- **EmployeeName** — Full name  
- **Department** — Business unit (Production, IT/IS, Sales, etc.)  
- **PositionID / Position** — Job role  
- **ManagerID / ManagerName** — Reporting line  
- **Gender, RaceDesc, CitizenDesc** — Demographic attributes  
- **DateOfHire / DateOfTermination** — Employment timeline  
- **RecruitmentSource** — Hiring channel (Indeed, LinkedIn, Referral, etc.)  
- **Salary** — Annual compensation  
- **EngagementScore / SatisfactionScore** — Employee sentiment indicators  
- **AbsenceDays / AbsenceRate** — Attendance metrics  
- **PerformanceScore** — Rating from “Needs Improvement” to “Exceeds”  
- **TerminationReason** — Reason for leaving (career change, more money, unhappy, etc.)

### 3. Business Questions

This dashboard aims to answer critical HR operational questions:

#### Workforce Overview
- How many employees does the company have?
- What is the total salary expense?
- What is the average tenure, age, and satisfaction score?

#### Turnover & Retention
- What is the overall turnover rate?
- Which departments have the highest turnover?
- What are the top reasons employees leave?

#### Recruitment & Hiring
- Which recruitment sources bring the most hires?
- Are certain sources linked to higher retention?

#### Performance & Engagement
- How do satisfaction and engagement scores vary by department?
- Are high performers concentrated in specific teams?

#### Demographics & Diversity
- What is the gender distribution?
- How is the workforce distributed across age groups?

## II. Design Thinking Method

### Step 1: Empathize
Understand HR stakeholders’ needs: HR managers require a single source of truth to monitor workforce health, identify risks, and support decision making. They need visibility into turnover, performance, recruitment effectiveness, and demographic trends.

### Step 2: Define
Define the core problem: HR lacks a centralized operational dashboard that consolidates employee data, highlights risks, and provides actionable insights for workforce planning.

### Step 3: Ideate
Brainstorm potential solutions:
- Interactive Power BI dashboard  
- Department-level drilldowns  
- Visual storytelling for turnover, satisfaction, and demographics  
- Filters for manager, department, performance score  
- Workforce database page for employee-level insights  

### Step 4: Prototype
Build the first version of the dashboard:
- Executive Summary page  
- Workforce Metrics Overview  
- Age & Gender Distribution visuals  
- Departure Reason analysis  
- Recruitment Source breakdown  
- Employee database table with slicers  

### Step 5: Review
Validate with HR stakeholders:
- Ensure KPIs match HR reporting standards  
- Confirm definitions (turnover, tenure, absence rate)  
- Adjust visuals for clarity and usability  
- Finalize color themes and layout for professional presentation  
## III. Visualization

### 1. Executive Summary

<img width="1533" height="864" alt="image" src="https://github.com/user-attachments/assets/73369912-5ace-4663-ba32-9e23984bd4bd" />

### 2. Workforce Database Overview

<img width="3282" height="1841" alt="image" src="https://github.com/user-attachments/assets/3b4d826d-148a-4680-ac8e-dd05bf09ebd4" />

