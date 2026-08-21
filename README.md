Data Warehouse & Power BI Analytics Project

📌 Project Overview

This project is an end-to-end Data Analytics & Data Warehouse project built using SQL Server and Power BI.

The project focuses on transforming raw business data into a structured Star Schema, cleaning and preparing the data, and building an interactive Power BI dashboard for business analysis.

🏗️ Project Architecture

The project follows a Star Schema design consisting of:

- Fact Tables — transactional/business measures
- Dimension Tables — descriptive attributes used for analysis

Main Components

- Customer Dimension
- Professional Dimension
- Product / Item Dimensions
- Other supporting Dimensions
- Central Fact Table

🛠️ Tools & Technologies

- SQL Server
- SQL Server Management Studio (SSMS)
- Power BI
- DAX
- Power Query
- GitHub

🔄 Data Workflow

Raw Data
   ↓
SQL Server
   ↓
Data Cleaning & Transformation
   ↓
Dimension & Fact Tables
   ↓
Star Schema
   ↓
Power BI
   ↓
DAX Measures
   ↓
Interactive Dashboard

🧹 Data Preparation

The data preparation process includes:

- Removing duplicate records
- Handling NULL values
- Standardizing data
- Correcting data types
- Creating surrogate/business keys
- Preparing Dimension tables
- Preparing Fact tables
- Establishing relationships between tables

⭐ Data Warehouse Model

The final model follows the Star Schema approach:

             DIM_CUSTOMER
                   |
                   |
DIM_PROFESSIONAL — FACT_TABLE — DIM_PRODUCT
                   |
                   |
              DIM_DATE

This structure makes the model easier to analyze and improves the performance and maintainability of the Power BI report.

📊 Power BI Dashboard

The Power BI layer is used to create:

- KPIs
- Business Performance Analysis
- Customer Analysis
- Professional Analysis
- Product Analysis
- Trend Analysis
- Interactive Filters & Slicers

📈 Key Metrics

Examples of analytical measures include:

- Total Sales
- Total Customers
- Total Transactions
- Average Value
- Profit / Revenue Metrics
- Performance Analysis
- Top & Bottom Performers

🧠 SQL Skills Demonstrated

- SELECT / JOIN
- GROUP BY
- CASE
- CTEs
- Subqueries
- Window Functions
- Data Cleaning
- Aggregations
- Views
- Primary & Foreign Keys
- Star Schema Design
- Query Optimization

📊 Power BI Skills Demonstrated

- Power Query
- Data Modeling
- Relationships
- DAX Measures
- Calculated Columns
- KPI Cards
- Charts
- Slicers
- Interactive Dashboard Design

🎯 Project Goal

The main goal of this project is to demonstrate a complete Data Analytics pipeline, starting from raw data and ending with a professional business intelligence dashboard.

«Raw Data → SQL Data Warehouse → Star Schema → Power BI → Business Insights»

👨‍💻 Author

YOUSSEF HASSAN 

Data Analytics | SQL | Power BI
