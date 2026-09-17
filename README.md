# Superstore-Retail_Dashboard
Superstore exel dashboard 
📊 Excel Sales & Profit Dashboard

An interactive Excel Business Intelligence Dashboard built using Power Query, Power Pivot, DAX, PivotTables, Pivot Charts, Charts, Slicers, and Filters to analyze sales, profit, and profit margins across different business categories.

The project demonstrates an end-to-end data analytics workflow — from data transformation and data modeling to DAX analysis and dashboard visualization.

🎯 Project Objectives

The main objectives of this project are to:

Clean and transform raw business data using Power Query
Build a structured data model using Power Pivot
Create calculated business metrics using DAX
Analyze sales and profitability using PivotTables
Create interactive visualizations using Pivot Charts and Charts
Use Slicers and Filters for interactive analysis
Identify high-performing and low-performing product categories
Provide business insights that can support data-driven decision-making
❓ Business Questions

The dashboard was designed to answer questions such as:

What is the total sales generated?
What is the total profit?
What is the overall profit margin?
Which category generates the highest sales?
Which category generates the highest profit?
Which category has the highest profit margin?
Which categories have relatively low profitability?
How do sales and profit compare across categories?
How does the selected category affect the key performance indicators?
Can users interactively filter the dashboard to analyze specific segments?
🔄 Project Workflow
Raw Data
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Power Pivot
   ↓
Data Model / Relationships
   ↓
DAX Measures
   ↓
PivotTables
   ↓
Pivot Charts & Charts
   ↓
Slicers & Filters
   ↓
Interactive Excel Dashboard
1. Data Preparation

Raw data was imported into Excel and prepared for analysis.

2. Power Query

Power Query was used for:

Data cleaning
Removing unnecessary data
Formatting columns
Transforming data
Preparing the dataset for modeling
3. Power Pivot

The cleaned data was loaded into the Power Pivot Data Model.

Power Pivot was used to:

Create the analytical data model
Manage relationships between tables
Create reusable DAX measures
4. DAX Analysis

DAX measures were created to calculate important business KPIs such as:

Total Sales
Total Profit
Profit Margin
5. PivotTables & Pivot Charts

PivotTables were used to summarize the data by category, while Pivot Charts were used to visualize the results.

6. Dashboard

The final dashboard combines:

KPI metrics
PivotTables
Pivot Charts
Charts
Slicers
Filters

to provide an interactive analytical view.

🧩 Data Model

The project uses Power Pivot to create a structured data model.

The model contains business data organized for analytical reporting, with dimensions such as:

                ┌───────────────┐
                │   FactOrders  │
                │───────────────│
                │ Sales         │
                │ Profit        │
                │ Quantity      │
                │ Discount      │
                │ Product       │
                │ Customer      │
                │ Region        │
                └───────┬───────┘
                        │
          ┌─────────────┼─────────────┐
          ↓             ↓             ↓
   DimProducts      DimRegion     DimCustomers

The Power Pivot model allows the dashboard calculations and visualizations to work across related tables.

Note: Update the table names above to match the exact names used in your workbook.

🧮 DAX Measures

The dashboard uses DAX measures for KPI calculations.

Total Sales
Total Sales =
SUM(FactOrders[Sales])
Total Profit
Total Profit =
SUM(FactOrders[Profit])
Profit Margin
Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
Profit Margin %

The result is formatted as a percentage in Power Pivot.

These measures allow the dashboard to dynamically recalculate when users apply slicers and filters.

📊 Dashboard Features
KPI Analysis

The dashboard provides important business metrics including:

Total Sales
Total Profit
Profit Margin
Category Analysis

The dashboard compares:

Furniture
Office Supplies
Technology

using sales, profit, and profit margin.

Interactive Filtering

Users can interact with the dashboard using:

Slicers
Filters
PivotTable filters
Chart/PivotChart filters

This allows users to explore different portions of the dataset without manually changing the underlying data.

Visualizations

The dashboard includes:

PivotTables
Pivot Charts
Sales comparison charts
Profit comparison charts
Category-based analysis
📸 Dashboard Screenshot

Place the dashboard screenshot in the repository root and name it dashboard.png.

🔍 Key Findings

Based on the dashboard shown:

Sales by Category
Category	Total Sales
Furniture	$252,612.74
Office Supplies	$220,853.25
Technology	$251,991.83
Total	$725,457.82
Profit by Category
Category	Total Profit
Furniture	$11,504.95
Office Supplies	$52,609.85
Technology	$44,303.65
Total	$108,418.45
Profit Margin
Category	Profit Margin
Furniture	4.55%
Office Supplies	23.82%
Technology	17.58%
Overall	14.94%
Dashboard Observations
Furniture generated $252.6K in sales but had a relatively low 4.55% profit margin.
Office Supplies generated approximately $220.9K in sales and $52.6K profit.
Technology generated approximately $252.0K in sales and $44.3K profit.
Total sales were approximately $725.5K.
Total profit was approximately $108.4K.
Overall profit margin was 14.94%.

These observations demonstrate why analyzing profit and profit margin alongside sales is important rather than looking at sales alone.

🛠️ Tools & Technologies
Tool	Purpose
Microsoft Excel	Dashboard development
Power Query	Data cleaning & transformation
Power Pivot	Data modeling
DAX	Business calculations & KPIs
PivotTables	Data summarization
Pivot Charts	Interactive visualization
Charts	Data visualization
Slicers	Interactive filtering
Filters	Data exploration
📁 Repository Structure
Excel-Sales-Profit-Dashboard/
│
├── 📊 Excel_Sales_Dashboard.xlsx
│
├── 🖼️ dashboard.png
│
└── 📄 README.md
Files

Excel_Sales_Dashboard.xlsx
Main Excel workbook containing:

Raw/processed data
Power Query transformations
Power Pivot data model
DAX measures
PivotTables
Pivot Charts
Dashboard
Slicers and filters

dashboard.png
Screenshot of the completed dashboard.

README.md
Project documentation.

🚀 How to Use
Download the Excel workbook.
Open it using Microsoft Excel.
Go to the Dashboard sheet.
Use the available slicers and filters.
Select different categories or dimensions.
Observe how the KPIs, PivotTables, and charts update dynamically.
💡 Skills Demonstrated

This project demonstrates practical experience with:

Excel Data Analysis
Data Cleaning
Power Query
Power Pivot
Data Modeling
DAX
KPI Development
PivotTables
Pivot Charts
Interactive Dashboards
Business Analysis
Data Visualization
Extract, Transform & Load (ETL)
📌 Project Summary

This project demonstrates how Excel can be used as a complete BI and data analytics tool, combining Power Query + Power Pivot + DAX + PivotTables + interactive visualizations to transform business data into an analytical dashboard.

The dashboard focuses on sales, profit, and profitability analysis, allowing users to interact with the data through slicers and filters and quickly identify differences in business performance across categories.
