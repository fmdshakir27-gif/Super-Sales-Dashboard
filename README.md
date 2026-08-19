# 📊 Superstore Sales Dashboard | Power BI

## 📌 Project Overview

The **Superstore Sales Dashboard** is an interactive Power BI business intelligence project designed to analyze and monitor sales performance across **categories, sub-categories, regions, customer segments, and years**.

The dashboard provides a consolidated view of key business KPIs and helps identify sales trends, profitable categories, high-performing regions, and product-level performance.

## 🎯 Business Objective

The primary objective of this project is to transform raw Superstore sales data into an interactive dashboard that enables stakeholders to:

* Monitor overall sales and profit performance
* Analyze year-over-year sales trends
* Identify high-performing product categories and sub-categories
* Compare regional sales performance
* Track quantity sold and customer volume
* Support data-driven business decisions through interactive filtering

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculated metrics
* **Data Modeling** – Relationships and dimensional modeling
* **Microsoft Bing Maps** – Regional sales visualization

## 📈 Key KPIs

The dashboard tracks the following key performance indicators:

| KPI                 |    Value |
| ------------------- | -------: |
| Total Sales         |  $2.327M |
| Total Profit        | $292.30K |
| Total Quantity Sold |      39K |
| Total Customers     |      804 |

## 📊 Dashboard Features

### 1. Sales by Category

Analyzes sales contribution across:

* Technology
* Furniture
* Office Supplies

### 2. Sales Trend by Year

Provides a year-wise view of sales performance and highlights changes in sales over time.

### 3. Sales by Sub-Category

Identifies the highest-revenue sub-categories, including:

* Chairs
* Phones
* Storage
* Tables
* Binders
* Machines
* Accessories
* Copiers
* Bookcases
* Appliances

### 4. Sales & Profit Analysis

Compares yearly sales and profit to understand business growth and profitability trends.

### 5. Regional Sales Analysis

Uses a geographical visualization to compare sales performance across:

* Central
* East
* South
* West

### 6. Interactive Year Filter

Users can select a specific year to dynamically analyze the dashboard metrics and visualizations.

## 💡 Key Insights

Based on the dashboard:

* **Technology** is the highest-performing category by sales.
* **Chairs** generate the highest sales among the displayed sub-categories.
* Sales show an overall upward trend across the analyzed years.
* **2026** records the highest annual sales in the dashboard.
* Profit also shows a positive trend alongside sales growth.
* Regional analysis provides visibility into differences in sales performance across the United States.

## 🧮 DAX Measures

Example measures used in the project:

```DAX
Total Sales =
SUM(Orders[Sales])

Total Profit =
SUM(Orders[Profit])

Total Quantity =
SUM(Orders[Quantity])

Total Customers =
DISTINCTCOUNT(Orders[Customer ID])
```

## 🔄 Data Preparation

The dataset was prepared using **Power Query** before building the dashboard.

Key transformation steps included:

1. Removing unnecessary columns
2. Checking and correcting data types
3. Handling missing or invalid values
4. Removing duplicate records where required
5. Creating appropriate relationships
6. Validating numerical and categorical fields
7. Loading the cleaned dataset into the Power BI data model

## 🏗️ Data Modeling

The Power BI model was structured to support efficient analysis of sales, profit, customers, products, categories, and geographical dimensions.

The model was used to create relationships between relevant fields and enable dynamic filtering across dashboard visuals.

## 🎨 Dashboard Design

The dashboard includes:

* KPI Cards
* Donut Chart
* Line Charts
* Horizontal Bar Chart
* Map Visualization
* Year Slicer
* Interactive filtering
* Consistent dark-theme visual design


This project was developed as a practical **Business Intelligence and Data Analytics portfolio project** to demonstrate the ability to transform raw sales data into an interactive, decision-oriented Power BI dashboard.
