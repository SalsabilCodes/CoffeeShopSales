# Coffee Shop Sales Analysis

This project analyzes the sales performance of a coffee shop using transactional data. The analysis aims to provide insights into sales trends, order quantities, and customer behavior over time, helping to identify opportunities for business growth and operational improvements.

## Project Status: Completed

## Project Overview

The project focuses on monthly sales analysis, order counts, and quantity sold, with detailed breakdowns by day, hour, product category, and store location. It includes calculations of month-on-month growth metrics, sales patterns by weekdays vs weekends, and visualization-friendly data modeling in Power BI.

The main objective is to deliver actionable KPIs and dynamic insights that can support decision-making for the coffee shop management.

## Data Source

The dataset was sourced from [Data Tutorials YouTube Channel](https://www.youtube.com/@datatutorials1), which provides a sample transactional dataset for practicing sales analysis.

## Methods Used

- SQL queries for data cleaning, aggregation, and KPI calculation
- Power BI for data modeling, measures, and visualization
- Time series and comparative analysis (month-on-month growth)
- Categorization and segmentation (weekdays/weekends, store locations, product types)

## Technologies

- MySQL (for data cleaning and SQL queries)
- Power BI (for data modeling and visualization)
- DAX (Data Analysis Expressions) for creating dynamic measures

## Project Details

### Data Cleaning in MySQL

- Converted transaction_date from string to DATE datatype.
- Converted transaction_time from string to TIME datatype.
- Renamed the transaction_id column for consistency.

### SQL Queries

- Total sales, total orders, and total quantity sold by month.
- Month-on-month difference and growth percentage calculations using window functions.
- Daily sales, weekday/weekend sales segmentation.
- Sales by store location and product categories.
- Top 10 products by sales volume.
- Sales breakdown by day of week and hour of day.


### Power BI Data Modeling

- Created a Date Table with month, month number, day name, and weekday/weekend classification.
- Established relationships between the Date Table and the Transactions table.
- Created calculated columns and measures for sales, orders, quantity sold, and their month-on-month growth.
- Implemented measures for dynamic filtering by month and store location.
- Created visual indicators (e.g., color coding for above/below average sales).
- Developed custom labels combining categories with sales amounts for clearer visualization.

### Visualizations (implemented in Power BI)

- Calendar heatmap showing daily sales volume with tooltips.
- Sales trends with average sales line and highlight on days above/below average.
- Sales comparison across weekdays and weekends.
- Store location and product category performance.
- Top 10 product sales ranking.
- Sales heatmap by day and hour.

## How to Use This Repository

1. Clone or download the repository.
2. Use the provided SQL scripts to clean and prepare your data in MySQL.
3. Load the cleaned dataset into Power BI.
4. Use the provided DAX measures and data model to reproduce the analysis.
5. Customize the reports and visualizations as needed.



