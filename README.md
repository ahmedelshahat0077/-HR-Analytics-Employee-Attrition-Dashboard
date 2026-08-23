# 📊 HR Analytics for Atlas Lab: How Data Uncovers the Hidden Drivers of Employee Attrition

<img width="1594" height="624" alt="19-30-21" src="https://github.com/user-attachments/assets/089fdf6b-6719-493f-9c69-df2f51f108f9" />


# 📌 Executive Summary
Employee attrition presents a major financial and operational burden. In this case study for Atlas Labs, I developed an end-to-end interactive dashboard in Power BI to analyze employee demographics, work environments, and retention metrics. By combining operational features like overtime and business travel with performance data, the analysis isolates the exact high-risk employee profiles to enable proactive HR interventions.

# 🛠️ Tools & Technologies Used
Power BI Desktop: Core tool used for data modeling, visualization, and interactive dashboard layout.

Power Query (M): Used for ETL processes—cleaning raw datasets, unpivoting attribute tables, handling null values, and validating data types.

DAX (Data Analysis Expressions): Implemented for custom metrics, inactive relationship management (USERELATIONSHIP), dynamic measures, and Time Intelligence logic.

# 🔄 Project Workflow: Step-by-Step Implementation
Business Problem Definition: Identified key business questions around why the baseline attrition rate sits at 16% and which operational factors drive high-performing staff out.

Data Transformation & Cleaning (Power Query):

Handled missing values, standardized categorical columns (e.g., Overtime status, Travel Frequency).

Formatted dates (HireDate, ExitDate) to build a normalized data model.

Data Modeling (Star Schema):

Linked dimension tables (Dim_Employee, Dim_Department, Dim_Calendar) to the central Fact table.

Managed dual date relationships using USERELATIONSHIP to calculate employee hires and exits independently.

DAX Development: Created essential KPIs for baseline headcount, leavers count, and dynamic turnover percentages.

Dashboard Design : Engineered an executive dashboard split across overview metrics, departmental deep-dives, and employee risk profiling.

# 🔑 Key Findings & Data Patterns
🔥 The Overtime Factor (Burnout Alert): While the company baseline attrition rate is 16%, it nearly doubles to 30.5% for employees working regular overtime—highlighting heavy burnout and workload fatigue.

# 💼 High-Risk Roles:

Sales Representatives: Suffer from the highest attrition rate across the firm, peaking at ~40%.

HR Recruiters: High turnover driven by non-stop recruitment cycle pressures.

Data Scientists: Elevated departure rates attributed to strong external market poaching and competitive talent demand.

✈️ Travel Frequency Fatigue: Employees required to travel frequently (Frequent Travel) record a 25% attrition rate, significantly higher than non-traveling peers.

⏳ Early Tenure Drop-Off: Attrition is heavily concentrated among first-year hires (< 1 year tenure), stabilizing sharply as tenure progresses and dropping to minimal levels past the 10-year mark.

# 💡 Strategic Recommendations for HR Leadership
Cap Overtime & Restructure Travel: Introduce policy caps on weekly overtime, establish compensatory time-off policies, and adjust travel rotation allowances to curb physical burnout.

Overhaul the First-Year Onboarding: Design a structured 90-day onboarding and mentorship framework specifically targetting new hires to address early-stage departures.

Role-Specific Retention Packages: Benchmark compensation packages, performance bonuses, and career growth tracks for critical roles (Sales, Recruiting, Data Science) against top market standards.

# 📸 Dashboard Screenshots & Demo
(حط الصور أو الـ GIF الخاص بك هنا)

1. Executive Summary Page
2. Attrition & Overtime Deep-Dive
