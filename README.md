🏭 Manufacturing Analytics Project
📊 End-to-End Data Analysis Using Excel • MySQL • Tableau • Power BI
📌 Project Overview

This project focuses on analyzing manufacturing performance data to understand production trends, rejection patterns, wastage levels, and efficiency across different departments, machines, buyers, and employees.
The objective is to build a complete analytical workflow starting from raw data → cleaning → SQL querying → dashboard creation → insights generation.

🎯 Objectives

Analyze total manufactured, processed, and rejected quantities
Identify departments, machines, buyers, and employees contributing to high rejections
Build interactive dashboards for decision-making
Create an end-to-end analytics pipeline using Excel, SQL, Tableau, and Power BI

🗂️ Tools & Technologies Used
Tool	Purpose
Excel	Data cleaning, preprocessing, Pivot analysis
MySQL	Querying, data modeling, aggregations
Tableau	Visual analytics and interactive dashboards
Power BI	KPI dashboards, DAX calculations, root cause analysis
📁 Project Structure
📦 Manufacturing-Analytics-Project
 ┣ 📂 Excel
 ┃ ┗ Cleaned datasets, Pivot tables, summary reports
 ┣ 📂 SQL
 ┃ ┗ MySQL queries, joins, aggregations, and outputs
 ┣ 📂 Tableau
 ┃ ┗ Tableau workbook (.twb/.twbx) and dashboard images
 ┣ 📂 PowerBI
 ┃ ┗ PBIX file and dashboard screenshots
 ┗ 📄 README.md (this file)

🧹 1. Data Cleaning (Excel)

Removed duplicates, blanks, formatting issues
Created Pivot Tables for monthly production
Applied conditional formatting for high rejection identification
Initial KPI validation using Excel formulas

🗄️ 2. MySQL Data Analysis

Performed SQL operations including:
✔ Joins
✔ Aggregations
✔ Department-wise & machine-wise summaries
✔ Monthly rejection trend queries

Example SQL Query:

SELECT Department, SUM(RejectedQty) AS Total_Rejections
FROM manufacturing_data
GROUP BY Department
ORDER BY Total_Rejections DESC;

📈 3. Tableau Dashboard

Created interactive dashboards with:
Department-wise rejection heatmaps
Monthly production trends
Buyer-wise and machine-wise performance
Filters for department, machine, and employee
Key Insight:
Woven Labels department shows consistently higher rejection percentage.

📊 4. Power BI Dashboard

Designed a complete multi-page dashboard with:
⭐ KPIs
Total Manufactured Qty: 60M
Total Orders: 10K
Total Rejected Qty: 491K
Wastage %: 0.01
Efficiency: 99.14%

⭐ Pages
🔹 Manufacturing Dashboard (Main Page)
Department-wise production & wastage
Buyer-wise rejected quantity
Employee & machine analysis
Monthly production trends
🔹 Expanded Insights – Part 1
Donut charts
Decomposition Tree
Root cause identification
🔹 Expanded Insights – Part 2
Key Influencers visual
Statistical factors that drive rejection increase/decrease

⭐ Features Used
DAX Measures
Dynamic Titles
Drill-through
Key Influencers
Decomposition tree
Slicers & Filters

🔍 Key Insights From the Project

Woven Labels has the highest wastage ratio
MC027 and MC026 machines contribute most to rejections
Shruti Singh leads employee-level rejections
Peak production months: March (5.4M) and June (5.25M)
SQL + Power BI pipeline optimized data processing and visualization

🚀 Project Highlights

Complete end-to-end analytics project
Integrated workflow across four tools
Strong visualization and storytelling
Clear KPI-driven performance tracking
Root-cause driven insights

📚 Learnings

Practical experience with ETL, SQL, and BI tools
Building dashboard-driven narratives
DAX, dynamic titles, and advanced Power BI visuals
Combining multiple tools to solve a real business problem

🤝 Feel Free to Explore or Fork

All files are well-organized inside tool-specific folders.
Use this project as a reference for:
Interviews
Portfolio
Academic submissions
BI/Data Analyst job applications

📬 Contact
If you have questions or suggestions, feel free to reach out!
