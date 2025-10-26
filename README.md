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

### 3. Data Modeling
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

## Dashboard interaction
- <a href="https://github.com/Atif20004/blinkit-grocery-analytics-dashboard/blob/main/Screenshot%202025-10-25%20164948.png"> View Dashboard</a>

## Dashboard
<img width="1319" height="745" alt="Screenshot 2025-10-25 164948" src="https://github.com/user-attachments/assets/fc156317-e15d-412c-a7ab-e563e8afb94b" />

## Dashboard Overview
### Top KPI Cards
total_sales — $1.2M 

Avg_sales — 141 average per item

No of Items — 8,523 products analyzed

Avg_rating — 3.92 customer satisfaction

### Filters & Interactivity (Slicers)
Location Type — filter by city tier classification (All/Tier 1/Tier 2/Tier 3)

Outlet Size — small, medium, high capacity analysis (All sizes available)

Outlet Type — supermarket type comparison (All types available)

Item Type — category-specific performance view (All categories available)

### Visuals Used
 Line Chart — total_sales by Outlet Establishment Year (showing trend from 2012-2022 with peak at $205K in 2018)

 Pie Chart — Sum of Sales by Outlet Size (Medium: 507.90K, Small: 248.99K, High: 444.79K)

 Donut Chart — Fat by Outlet (Low Fat vs Regular distribution)

 Horizontal Bar Chart — Item Type sales breakdown (showing categories like Fruits and Vegetables, Snack Foods, Household, etc.)

 Stacked Bar Chart — Fat Content analysis across outlet location types

 Summary Table — Outlet Type performance showing total_sales, Avg_sales, No of items, Avg_rating, and Sum of Item Visibility for each outlet type (Supermarket Type1, Grocery Store, Supermarket Type2, Supermarket Type3)

 Pie Chart — Sum of Sales by Outlet Location Type (Tier 3: 472.13K, Tier 2: 393.15K, Tier 1: 336.40K, showing 71.3% concentration)

 ## Key Insights
•	Total Revenue: $1.2M generated across all BlinkIT outlets

•	Outlet Performance: Tier 3 locations lead with 472.13K in sales, showing strong performance in smaller cities

•	Product Categories: Fruits & Vegetables, Snack Foods, and Household items are top-performing categories

•	Fat Content Preferences: Low Fat products account for $425.36K vs Regular at $776.32K in sales

•	Store Format Success: Supermarket Type1 demonstrates highest sales ($787.55K) followed by Grocery Store ($151.94K), Supermarket Type2 ($131.48K), and Supermarket Type3 ($130.71K)

•	Rating Consistency: Stable 3.9+ ratings across all outlet types indicating consistent customer satisfaction

•	Establishment Trends: Peak sales observed in 2018 outlets, showing maturity curve

•	Medium Outlets Dominate: Medium-sized outlets generate the highest sales (507.90K) compared to small (248.99K) and high-capacity stores (444.79K)

## Final Conclusion & Personal Reflection
This project demonstrates my ability to transform raw retail data into actionable business insights through effective use of Power BI. By building this dashboard from the ground up, I gained hands-on experience in data cleaning, DAX measure creation, interactive visualization design, and storytelling with data.

### What this dashboard delivers:

Clear visibility into sales performance across outlets, product categories, and customer segments

Identification of top-performing store formats and high-demand product types

Insights into regional performance variations and customer rating trends

A user-friendly interface that empowers stakeholders to explore data independently

### Key learnings from this project:

Practical application of Power BI features including slicers, calculated measures, and cross-filtering

Understanding of retail business metrics and how location, product type, and store format impact revenue

Development of analytical thinking to translate business questions into visual insights

Experience in designing professional, clean dashboards that balance aesthetics with functionality

### Challenges overcome:

Managing data relationships and ensuring accurate calculations across multiple dimensions

Choosing the right visualizations to communicate insights clearly

Maintaining consistent formatting and user experience throughout the dashboard

This project reflects my commitment to continuous learning and my readiness to contribute as a data analyst. I built it independently through iterative improvement, ensuring every metric, visual, and insight adds real value for decision-makers.



