#HR Analytics Dashboard
📊 HR Analytics Dashboard — Employee Insights & Attrition Analysis

An interactive Power BI dashboard that analyzes employee demographics, satisfaction, and attrition patterns to help HR teams understand why employees leave and how to retain them.

#Description / Purpose

The HR Analytics Dashboard is a 3-page Power BI report designed to help HR managers and business leaders track workforce composition, monitor attrition trends, and identify the key drivers behind employee turnover. It consolidates employee-level data into clear KPIs, charts, and filters so that HR teams can move from raw data to actionable retention strategies.

#Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main data visualization platform used for report creation.
📁 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
🧮 DAX (Data Analysis Expressions) – Used to build measures such as Total Employees, Active Employees, Attrition Rate, Attrition Count, and Average Salary.
🗂️ Data Modeling – A single fact table (HR data) with calculated columns (Age Group, Salary Band, Working Year Intervals) enabling filtering and cross-visual interaction.

#Data Source

The dashboard runs on a single dataset — HR data — containing employee-level records with fields including:

#Demographics: Gender, Age Group, Marital Status, Education Field
#Job details: Department, Job Role, Business Travel, Over Time
#Compensation & tenure: Avg Salary, Salary Band, Total Working Years, Working Year Interval (at company / in current role)
#Satisfaction metrics: Job Satisfaction, Environment Satisfaction, Relationship Satisfaction, Work-Life Balance
#Attrition fields: Attrition (Yes/No), Attrition Count, Attrition Rate, Attrition Employees, Active Employees, Total Employees

#Business Problem

Organizations often struggle to identify why employees leave and which segments of the workforce are most at risk, making it hard to design targeted retention strategies before turnover impacts productivity and cost.

#Key questions such as:

Which departments and job roles have the highest attrition?
How does attrition vary by age group, gender, overtime, and business travel?
Does job satisfaction or tenure correlate with attrition?
What does the overall workforce composition look like (department, gender, education, marital status)?
Goal of the Dashboard

To give HR stakeholders a single, filterable view of workforce health — from high-level KPIs down to attrition drivers — so they can spot at-risk segments and act on them.

#Walkthrough of Key Visuals (by page)

1. HR Overview

KPI cards: Total Employees, Active Employees, Attrition Employees, Attrition Rate, Average Salary
Employee Attrition by Department (clustered bar chart)
Employee Attrition by Job Role (column chart)
Attrition by Department (donut chart)
Attrition Rate by Gender across age bands: Under 25, 25–34, 35–44, 45–54, Over 55 (donut charts)

2. Employee Demographics

Slicers: Department, Gender, Age Group
Employee Distribution by Department (clustered bar chart)
Employee Distribution by Job Role (stacked area chart)
Employee Distribution by Gender (donut chart)
Employee Distribution by Age Group (clustered column chart)
Employee Distribution by Education Field (bar chart)
Employee Marital Status by Gender (donut chart)

3. Attrition Analysis

KPI cards: Attrition Count, Average Tenure, Average Satisfaction, Attrition Rate
Slicers: Department, Gender, Age Group, Education Field
Employee Attrition by Overtime (column chart)
Attrition by Business Travel (donut chart)
Employee Attrition by Tenure at Company (clustered bar/column charts)
Employee Attrition Rate by Satisfaction Score (100% stacked column chart)
Business Impact & Insights
Retention Strategy: HR teams can pinpoint departments and job roles with the highest attrition and prioritize interventions.
Workforce Planning: Understanding demographic and tenure distribution helps plan hiring and succession pipelines.
Risk Segmentation: Cross-referencing overtime, business travel, and satisfaction scores with attrition helps flag high-risk employee segments early.
Data-Driven Decisions: Replaces manual HR reporting with a live, filterable dashboard that leadership can explore directly.
Key Takeaways

Based on the actual dataset powering this dashboard (1,470 employees):

#Overall attrition rate: 16.1% — 237 of 1,470 employees have left; 1,233 are active. Average monthly income is ₹6,503.
#Overtime is the strongest driver of attrition: employees who work overtime leave at 30.5%, nearly 3x the rate of those who don't (10.4%).
#Younger employees are the highest flight risk: Under-25 attrition is 39.2%, compared to ~10% for the 35–54 age bands.
#Sales Representatives churn the most of any job role (39.8%), followed by Laboratory Technicians (23.9%) and HR (23.1%). Research Directors (2.5%) and Managers (4.9%) are the most stable roles.
#Single employees leave more than twice as often as married employees (25.5% vs 12.5%).
#Frequent travelers attrite at 24.9%, over 3x the rate of non-travelers (8.0%).
#Low job satisfaction and poor work-life balance strongly predict attrition: satisfaction score 1 sees 22.8% attrition (vs 11.3% at score 4); work-life balance #score 1 sees 31.2% attrition, roughly double every other tier.
#Sales has the highest departmental attrition rate (20.6%), but R&D loses the most employees in absolute terms (133 of 237 leavers) simply due to its larger headcount.
#Leavers have shorter average tenure (5.1 years) than stayers (7.4 years) — attrition risk is concentrated in the earlier years of employment.

#Profile of a flight-risk employee: young, single, working overtime, traveling frequently, in Sales or an entry-level technical role, with low satisfaction and work-life balance scores. This is the segment HR should prioritize for retention efforts.



