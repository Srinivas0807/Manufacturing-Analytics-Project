# 🏭 Manufacturing Analytics Project

### 📊 End-to-End Data Analysis Using Excel • MySQL • Tableau • Power BI

---

## 📌 Project Overview

This project analyzes **manufacturing performance** to understand production trends, rejection patterns, wastage %, and efficiency across departments, machines, employees, and buyers.
The goal is to build a **complete analytics pipeline** using **Excel → MySQL → Tableau → Power BI**.

---

## 🎯 Objectives

* Analyze monthly and department-wise manufacturing trends
* Identify root causes of high rejection and wastage
* Build interactive dashboards in Tableau and Power BI
* Use SQL for querying and preprocessing
* Present actionable insights for improving efficiency

---

## 🛠️ Tools & Technologies

| Tool         | Purpose                                      |
| ------------ | -------------------------------------------- |
| **Excel**    | Data cleaning, preprocessing, Pivot analysis |
| **MySQL**    | SQL queries, joins, aggregations             |
| **Tableau**  | Interactive visualization dashboard          |
| **Power BI** | KPI dashboards, DAX, advanced visuals        |

---

## 📁 Project Structure

```
📦 Manufacturing-Analytics-Project
 ┣ 📂 Excel
 ┃ ┗ Cleaned data, Pivot tables
 ┣ 📂 SQL
 ┃ ┗ SQL scripts & output
 ┣ 📂 Tableau
 ┃ ┗ Tableau workbook + dashboard images
 ┣ 📂 PowerBI
 ┃ ┗ PBIX file + dashboard screenshots
 ┗ 📄 README.md
```

---

## 🧹 1. Data Cleaning (Excel)

* Removed duplicates and missing values
* Standardized columns and formats
* Used Pivot Tables for preliminary analysis
* Applied conditional formatting to highlight high rejections

---

## 🗄️ 2. MySQL Queries & Analysis

Performed joins, aggregations, machine-level summaries, and rejection trends.

### ✔ Sample SQL Query

```sql
SELECT Department, SUM(RejectedQty) AS Total_Rejections
FROM manufacturing_data
GROUP BY Department
ORDER BY Total_Rejections DESC;
```

---

## 📈 3. Tableau Dashboard

Created interactive dashboards containing:

* Department-wise rejection heatmaps
* Monthly production and rejection trends
* Machine and buyer performance
* Filters for department, buyer, employee

**Key Insight:**

> Woven Labels department shows the highest rejection percentages consistently.

---

## 📊 4. Power BI Dashboard

### ⭐ Key KPIs

* **Total Manufactured Qty:** 60M
* **Total Orders:** 10K
* **Total Processed Qty:** 60M
* **Total Rejected Qty:** 491K
* **Wastage %:** 0.01
* **Production Efficiency:** 99.14%

### ⭐ Pages in Power BI

#### 🔹 Manufacturing Dashboard (Main Page)

* Department-wise production vs wastage
* Buyer-wise rejected quantity
* Employee rejection analysis
* Machine performance
* Monthly production trend

#### 🔹 Expanded Insights – Part 1

* Donut chart summary
* Decomposition Tree to track root causes
* Path: **Woven Labels → MC027 → Shruti Singh → Nike**

#### 🔹 Expanded Insights – Part 2

* Key Influencers visual showing drivers of rejection
* Operations like Cross Checking & Packing have highest averages

### ⭐ Advanced Features Used

* DAX Measures
* Dynamic Titles
* Drillthrough
* Key Influencers (AI Visual)
* Decomposition Tree
* Slicers & Filters

---

## 🔍 Key Insights

* **Woven Labels** shows the highest wastage ratio
* Machines **MC027** & **MC026** have highest rejections
* **Shruti Singh** tops in employee rejection quantity
* Peak production months: **March** & **June**
* MySQL + Power BI pipeline improved processing & modeling

---

## 🚀 Project Highlights

* Complete end-to-end analytics pipeline
* Multi-tool integration (Excel → SQL → Tableau → Power BI)
* KPI-driven dashboard design
* Professional data storytelling
* Deep-dive insights using advanced BI visuals

---

## 📚 Learnings

* Hands-on experience with SQL, DAX, Tableau, Power BI
* Data modeling & preprocessing
* Creating business-ready dashboards
* Understanding manufacturing workflows & KPIs

---

## 📦 How to Use This Repository

1. Open **Excel** folder → explore datasets
2. Run SQL scripts in **MySQL**
3. Open **Tableau** workbook for visual analysis
4. Open **Power BI (.pbix)** file to interact with dashboards
5. Review screenshots for quick insights

---

## 📬 Contact

If you’d like to collaborate or have suggestions, feel free to reach out!
