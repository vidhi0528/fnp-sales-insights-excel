# FNP Sales Analysis Dashboard (Excel)
This project focuses on analyzing sales data from **FNP (Ferns N Petals)**, a gifting platform that specializes in delivering gifts for various occasions such as Diwali, Raksha Bandhan, Birthdays, and more.
The goal of the project is to extract key insights into **sales performance**, **customer behavior**, and **product trends** using Excel with **Power Query**, **Power Pivot**, and **Pivot Charts**.

## Problem Statement
You have been provided with a dataset from FNP containing details of **product orders**, **customer information**, and **order timelines**. 
Your task is to analyze this dataset to uncover actionable insights related to:
- Sales trends by occasion, category, and month
- Customer behavior and average spend
- High-performing products and cities
- Operational metrics like order delivery time

## Tools & Technologies
- **Microsoft Excel**
- **Power Query Editor** (for ETL: Extract, Transform, Load)
- **Power Pivot** (Data modeling)
- **Pivot Tables & Measures** (DAX)
- **Interactive Dashboard with Charts & Slicers**

## Project Workflow

### 1.Data Extraction
- Extracted raw data using **Power Query's folder function** to load multiple files automatically.

### 2.Data Cleaning & Transformation
- Handled missing values, removed duplicates, and standardized columns.
- Converted data types, extracted date elements, and created calculated columns for analysis.

### 3.Data Modeling
- Built a **star schema** using:
- Orders table as the **Fact Table**
- Products, Customers, and Dates as **Dimension Tables**
- Created relationships using **Power Pivot**

### 4.Data Analysis
- Built Pivot Tables and used **DAX measures** for metrics like:
- Total Revenue
- Average Order Delivery Time
- Average Customer Spend
- Top Categories / Cities / Products

### 5.Dashboard Creation
- Created an interactive Excel dashboard with:
- Revenue breakdown by **occasion**, **category**, **month**, **day**, and **city**
- Slicers for dynamic filtering by **date**, **occasion**, and **category**
- KPIs: Total Orders, Revenue, Average Delivery Time, Avg Spend

## Screenshot of Dashboard

![Dashboard Preview](https://github.com/vidhi0528/fnp-sales-insights-excel/blob/main/Dashboard%20Snapshot.png)

## Key Insights
- Diwali and Raksha Bandhan are the highest revenue-generating occasions.
- Top revenue categories include Flower Bouquets and Gift Boxes.
- The average customer spends ₹3,520 per order.
- Most orders are delivered within 5.5 days.
- Major cities like Delhi and Mumbai account for the highest number of orders.

