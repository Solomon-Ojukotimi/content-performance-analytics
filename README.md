# content-performance-analytics
# Content Performance Analytics: Growth, Reach & Engagement Diagnostics

# **Project Overview**

This project analyzes multi-year content performance data to understand how production scale, audience reach, and engagement efficiency interact over time.

The goal was not just to track views and reads, but to engineer meaningful performance ratios that diagnose content scalability, audience conversion strength, and engagement concentration risk.

The dashboard is structured across three analytical layers:

* Executive Overview

* Engagement Efficiency & Tradeoff Analysis

* Article & Author-Level Diagnostics

# 📊 Key Business Questions

* Is content production scaling efficiently?

* Does higher output dilute engagement conversion?

* How concentrated is engagement across top-performing articles?

* Are member-only articles structurally more efficient?

* Which authors and articles drive engagement quality vs volume?

# 📈 Engineered KPIs

Instead of relying on raw totals, I designed performance ratios:

* Read Conversion Rate – Reads ÷ Views

* Engagement Yield – (Claps + 2×Responses) ÷ Reads

* Content Consumption Intensity – Average Reads per Published Article

* Engagement Concentration Ratio – % of total engagement driven by top 20% of articles

These metrics shift focus from scale to efficiency and structural performance.

# 🔎 Key Insights

* Production growth is positively correlated with engagement efficiency, suggesting scalability rather than content dilution.

* Engagement remains highly concentrated, with the top 20% of articles driving ~74% of total interactions.

* Member-only content consistently shows stronger engagement intensity.

* Increased output in later years does not negatively impact conversion efficiency.

* This suggests improved content-market alignment and editorial optimization over time.

# ⚙️ Data Modeling & Technical Approach

* Star schema model

* Time intelligence for MoM and YoY analysis

* Top 20% dynamic ranking using DAX

* Engagement ratio engineering with volatility controls

* Conditional formatting for performance categorization

* Production vs Efficiency scatter diagnostic analysis

# 📂 Dashboard Structure
**Page 1 – Executive Overview**

High-level KPI trends, reach vs reads comparison, and output trajectory.

**Page 2 – Engagement Analysis**

Efficiency diagnostics, concentration risk, and production tradeoff analysis.

**Page 3 – Author & Content Insights**

Article-level performance breakdown and author contribution analysis.

# 🛠 Tools Used

* Power BI

* DAX

* Data Modeling (Star Schema)

* Ratio Engineering

* Performance Segmentation

# 📌 Why This Project Matters

This project demonstrates analytical thinking beyond descriptive dashboards. It focuses on performance structure, scalability, and engagement quality with key drivers in content strategy and digital analytics environments.
