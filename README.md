# Retail Sales Intelligence Dashboard (Excel)

## Overview

This project is an interactive **Retail Sales Intelligence Dashboard** built using Microsoft Excel.
The goal of the project is to analyze retail sales data and transform raw transaction data into meaningful business insights.

Using Excel features such as **Power Query, Pivot Tables, formulas, and interactive slicers**, the dashboard helps understand sales trends, regional performance, and product profitability.

The dataset used is the well-known **Superstore dataset**, which contains approximately 9,000 retail transactions.

---

# Dataset

The dataset contains sales transaction records including:

* Order ID
* Order Date
* Customer Segment
* Region
* Product Category & Sub-Category
* Sales
* Quantity
* Profit

These fields allow analysis of **revenue performance, customer segments, and regional sales trends**.

---

# Workbook Structure

## 1. Raw_Data

This sheet contains the **original dataset** imported into Excel without any modifications.
It serves as the base data source for the project.

---

## 2. Clean_Data

Data cleaning was performed using **Power Query** to prepare the dataset for analysis.

Main steps performed:

* Removed duplicate rows
* Corrected data types (dates, numbers, text)
* Trimmed and cleaned text fields
* Created a new calculated column: **Shipping Days**

This step ensures the dataset is consistent and analysis-ready.

---

## 3. KPI

This sheet calculates important business metrics using Excel formulas.

Key metrics include:

Total Sales
=SUM(Superstore_Data[Sales])

Total Profit
=SUM(Superstore_Data[Profit])

Total Orders
=COUNTA(Superstore_Data[Order ID])

Average Order Value
=SUM(Superstore_Data[Sales]) / COUNTA(Superstore_Data[Order ID])

Profit Margin
=SUM(Superstore_Data[Profit]) / SUM(Superstore_Data[Sales])

Total Quantity Sold
=SUM(Superstore_Data[Quantity])

These KPIs summarize the overall performance of the business.

---

## 4. Pivot_Analysis

Pivot tables were created to perform deeper analysis of the data.

The following analyses were performed:

* Sales by Product Category
* Sales by Region
* Monthly Sales Trend
* Top Performing Products
* Profit by Customer Segment

These pivot tables act as the **data engine behind the dashboard visualizations**.

---

## 5. Dashboard

The final sheet presents an **interactive Excel dashboard** that summarizes the analysis.

The dashboard includes:

* KPI summary cards
* Sales vs Profit by Category
* Sales vs Profit by Region
* Monthly Sales Trend chart
* Interactive slicers for filtering by:

  * Customer Segment
  * Region
  * Product Category

Users can filter the dashboard dynamically to explore the data from different perspectives.

---

# Key Insights

Some of the insights discovered from the analysis include:

• The **Technology category** generates the highest revenue
• The **West region** contributes the highest profit
• Higher discount levels significantly reduce profit margins
• The **Corporate segment** shows the highest average order value

These insights demonstrate how Excel dashboards can support **data-driven decision making**.

---

# Skills Demonstrated

This project showcases the following data analytics skills:

* Microsoft Excel
* Power Query (Data Cleaning)
* Pivot Tables
* Data Visualization
* KPI Analysis
* Interactive Dashboards
* Business Insight Generation

---

# Project Outcome

This project demonstrates how Excel can be used as a **powerful business intelligence tool** to transform raw retail sales data into actionable insights through data cleaning, analysis, and visualization.

---

# Author

**Parth Bhadane**

Aspiring Data Analyst focused on building practical analytics projects using Excel, SQL, and data visualization tools.
