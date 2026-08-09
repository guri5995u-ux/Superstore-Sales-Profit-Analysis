# Superstore Sales & Profit Analysis 

## Project Overview

This project is a Power BI-based sales and profitability analysis using the Superstore dataset.

The objective is to analyze overall business performance, sales trends, profitability, customer segments, product categories, and regional performance using **Power BI and DAX**.

The project was developed as part of a Data Analytics / Power BI assignment.

---

## Tools & Technologies

- Power BI Desktop
- DAX
- Microsoft Excel
- Power BI Data Modeling
- Data Visualization

---

## Dataset

The project uses the Superstore dataset containing information related to:

- Orders
- Customers
- Products
- Sales
- Profit
- Quantity
- Regions
- Categories
- Customer Segments
- Returns

The dataset contains approximately 9,994 order records.

---

## Data Analysis Performed

The analysis focuses on the following business areas:

### 1. Overall Performance

Key Performance Indicators (KPIs):

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Quantity

### 2. Sales Trend Analysis

A monthly sales trend was created to understand how sales changed over time.

### 3. Profit Trend Analysis

A monthly profit trend was created to identify changes in profitability over time.

### 4. Category Analysis

Sales and profit were analyzed across major product categories:

- Technology
- Furniture
- Office Supplies

### 5. Regional Analysis

Sales performance was analyzed across:

- West
- East
- Central
- South

### 6. Customer Segment Analysis

Sales contribution was analyzed across:

- Consumer
- Corporate
- Home Office

### 7. Return Analysis

The dataset's return information was also incorporated into the Power BI model to support return-related analysis.

---

## DAX Measures

Several DAX measures were created to calculate important business KPIs, including:

```DAX
Total Sales = SUM(Orders[Sales])
