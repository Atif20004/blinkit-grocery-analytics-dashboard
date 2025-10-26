# BlinkIT Grocery Sales Analytics Dashboard (Power BI Project)
## Role: Data Analyst

This project showcases analytical work using Power BI to explore grocery retail performance for BlinkIT (India's Last Minute App). The goal was to uncover insights about sales patterns, product performance, outlet characteristics, and customer ratings across various grocery categories and store formats.

The dashboard transforms raw grocery sales data into actionable insights for business managers, category managers, and analysts — revealing sales drivers and optimization opportunities across BlinkIT's grocery operations.

## Project Objective
The main objective of this project is to create an interactive Power BI dashboard that answers critical business questions related to grocery retail performance, including:
•	Which item types and categories generate the highest sales?

•	How do sales vary across different outlet sizes and locations?

•	What are the rating patterns across product categories?

•	Which outlet types perform best in terms of sales and customer satisfaction?

•	How do fat content preferences impact sales across different outlets?

•	What are the sales trends by establishment year and outlet characteristics?

## Dataset Used
- <a href="https://github.com/Atif20004/blinkit-grocery-analytics-dashboard/blob/main/BlinkIT%20Grocery%20Data%20(2).xlsx">Dataset</a>

## Key Questions & Expanded KPIs
### Primary KPIs
Total Sales — $1.2M across all outlets

Average Sales — 141 per item

Total Items — 8,523 unique products

Average Rating — 3.92 customer satisfaction score

### Additional KPIs & Analytical Questions
Top Performing Item Categories — based on sales volume

Outlet Performance Analysis — sales by size, type, and location tier

Fat Content Preferences — low fat vs regular product performance

Sales Trends — performance by establishment year (2012-2022)

Location Impact — Tier 1, 2, 3 city performance comparison

Product Visibility Analysis — shelf space and item weight impact on sales

Outlet Type Comparison — Supermarket Type1, Type2, Type3, and Grocery Store performance

## Project Process
### 1. Data Understanding
Analyzed dataset structure and identified key retail metrics

Differentiated product attributes from outlet characteristics

Validated data completeness across items, outlets, and sales records

### 2. Data Cleaning & Transformation (Power Query)
Standardized item categories and outlet classifications

Created calculated column for Item Fat Content (Low Fat vs Regular)

Ensured data consistency across outlet identifiers and establishment years

Handled missing values and ensured proper data types

#### 3. Data Modeling
Created a Metrics 2 table containing DAX measures:

total_sales — sum of all sales transactions

Avg_sales — average sales per item

No_of_items — count of unique products

Avg_rating — average customer rating across categories

Relationships: Connected the metrics table to the main BlinkIT Grocery Data table for dynamic calculations.

### 4. Dashboard Design
Implemented KPI cards for immediate business insights

Created trend visualizations for sales performance over time

Designed comparative charts for outlet and product analysis

Applied professional yellow-themed layout matching BlinkIT branding

