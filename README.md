# Personal Sales Performance Analysis

This project analyzes personal field sales data in Power BI to better understand sales performance, revenue trends, and conversion rates across different stages of the sales process.

---

# Project Overview

The goal of this project was to analyze real sales activity data collected during field sales operations and identify:

- What drives revenue
- Which stages of the sales funnel perform best or worst
- How sales performance changes over time
- Which weekdays generate the highest revenue
- Whether increased activity leads to better results

The project includes data cleaning in Power Query, DAX measures, KPI tracking, funnel analysis, and interactive visualizations.

# Dashboard Preview

The dashboard includes:

- KPI Cards
- Sales Funnel Analysis
- Conversion Rate Analysis
- Revenue Trends Over Time
- Revenue by Weekday
- Scatter Plots

---

# Dataset Description

| Column | Description |
|---|---|
| Calls | Number of customer contacts |
| Demos | Product demonstrations |
| Sits | Full sales presentations |
| Cash | Total revenue generated |

## Column Renaming

| Original Column | Renamed Column | Description |
|---|---|---|
| Bk Units | Physical Units | Units from selling physical products like books |
| Web Units | Digital Units | Units from selling digital subscriptions/apps |
| Total Units | Total Units | Total units from all sales |

> **Note:** One unit does not equal one product. Different products have different unit values.

Some columns like `Weak` and `Solid` were not used because their business meaning was unclear and they were not important for the main analysis.

---

# Data Cleaning & Transformation

Data cleaning was done in **Power Query** and included:

- Checking data types
- Renaming columns
- Handling missing values
- Creating calculated columns
- Creating a separate Date Table
- Creating a `Worked_Day` flag for working and non-working days

Non-working days were excluded from some performance calculations to avoid affecting averages and trend analysis.

---

# Tools & Technologies

- Power BI
- Power Query
- DAX
- Excel

---

# Key Insights

- Revenue depends more on the number of presentations (`Sits`) than on the number of customer contacts (`Calls`)
- High activity does not always lead to high revenue
- Thursday and Friday had the highest average revenue
- Conversion rates decrease at each stage of the sales funnel
- There is a positive relationship between presentations and revenue

---

# Recommendations

- Focus on increasing the number of full presentations (`Sits`)
- Improve conversion from Demo to Sit stages
- Focus more on high-performing weekdays
- Focus on quality of interactions, not only quantity
--- 
# Conclusion
The analysis showed that improving conversion in the middle and final stages of the funnel could help increase revenue the most. The project also showed that the quality of presentations has a bigger impact on sales results than activity alone.

<img width="1329" height="750" alt="image" src="https://github.com/user-attachments/assets/2cc9cb72-080a-420e-bb33-d0307f53e8be" />
