# Retail Sales Intelligence Dashboard (Excel)

![Dashboard Preview](dashboard-1.png)

## Project Overview

This project presents an interactive retail sales dashboard built using Microsoft Excel.
The goal of the project is to analyze retail sales data and transform raw transactional data into meaningful insights that help understand sales performance and profitability.

Using Excel tools such as Power Query, Pivot Tables, formulas, charts, and slicers, the dataset was cleaned, analyzed, and converted into an interactive dashboard that allows users to explore sales performance from different perspectives.

The dataset used in this project is the Superstore dataset, which contains around 9,000 retail transactions.

---

## Dataset Description

The dataset contains retail sales records with information such as:

* Order ID
* Order Date
* Customer Segment
* Region
* Product Category and Sub-Category
* Sales
* Quantity
* Profit

These fields allow analysis of sales trends, regional performance, and product profitability.

---

## Project Workflow

### 1. Data Preparation

Data cleaning and transformation were performed using Power Query.

The main steps included:

* Removing duplicate records
* Correcting data types such as dates and numeric values
* Cleaning text fields
* Creating a calculated column called Shipping Days

This step ensured the dataset was clean and ready for analysis.

---

### 2. KPI Calculation

Key business metrics were calculated using Excel formulas to summarize overall sales performance.

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

These metrics provide a quick overview of business performance.

---

### 3. Data Analysis

Pivot Tables were used to analyze the dataset from different perspectives, including:

* Sales by product category
* Sales by region
* Monthly sales trends
* Profit by customer segment

These pivot tables act as the analytical base for the dashboard.

---

### 4. Dashboard Development

An interactive Excel dashboard was created to present the analysis visually.

The dashboard includes:

* KPI summary cards
* Sales vs profit by category
* Regional sales performance
* Monthly sales trend
* Interactive slicers for filtering by segment, region, and category

The slicers allow users to interact with the dashboard and view different insights dynamically.

---

## Key Insights

Some insights discovered from the analysis include:

* The Technology category generates the highest revenue
* The West region contributes the highest profit
* Higher discount levels tend to reduce profit margins
* The Corporate segment has the highest average order value

These insights show how data analysis can support better business decisions.

---

## Skills Demonstrated

This project demonstrates the following skills:

* Microsoft Excel
* Power Query
* Pivot Tables
* Data Cleaning
* Data Visualization
* KPI Analysis
* Dashboard Development

---

## How to Use the Project

1. Download the Excel file from this repository
2. Open the file in Microsoft Excel
3. If Excel opens the file in Protected View, click Enable Editing
4. Use the slicers on the dashboard to explore the data interactively

---

## Author

Parth Bhadane

Aspiring data analyst interested in data analysis, business intelligence, and building practical analytics projects.
