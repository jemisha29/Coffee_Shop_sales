# Coffee_Shop_sales

### Dashboard Link : [https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection](https://app.powerbi.com/groups/me/reports/bdb26f3c-a708-4135-ae56-462425c95c7d/019e63eca73135b43cf9?experience=power-bi)

## Project Overview

This dashboard provides a comprehensive overview of sales performance for a coffee shop during 2023. It offers insights into key metrics such as total sales, orders, and quantity sold, as well as trends over time, sales by weekday/weekend, product category, top 10 products, and sales by day/hour.

## Problem Statement

This dashboard provides the coffee shop owner with valuable insights into sales patterns, offering a detailed overview of total sales across various categories and locations. By highlighting areas for improvement, the dashboard enables the owner to enhance services strategically. It also provides analysis of average sales by weekday, weekend, and specific hours, helping identify times with Higher sales. 

By using this dashboard, the owner can pinpoint problem areas and work on addressing the factors contributing to reduced sales, ultimately boosting overall performance.

## Data Sources

The primary dataset used for this analysis is the "Coffee Shop Sales.csv" file, containing detailed information about each transaction made by the shop.

Create a dedicated "Date" table using DAX to generate date-specific columns for granular analysis.

## Tools

* **Excel - Data Cleaning**
  * [Download here](https://github.com/jemisha29/Coffee_Shop_sales/blob/main/Coffee%20Shop%20Sales.csv)
* **SQL Server - Data Analysis**
* **PowerBI - Creating reports**

## Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:

### Excel
   - **Changing Data Types** : Ensured that numeric columns (e.g., sales amount, quantity sold, order ID) were set to appropriate numeric data types.
   - **Replacing Null Values** : Applied methods such as filling with mean/median for numeric fields.
   - **Formatting Cells** : Ensured proper formatting for columns, such as setting number formats with appropriate decimal places.
   - **Handling Missing Values** : Used Excel functions to fill or remove missing data.
   - **Categorizing Products and Locations** : Ensured consistent labeling for products and locations.
   - **Standardizing Date Formats** : Used Excel functions to convert date columns to a consistent format.

### Power BI
   - **Data Modeling** : Created a date table and connected it with the transaction table using the date column as the common key. This allows for time-based analysis and filtering in the dashboard.
   - **Conditional Formatting** : Used conditional formatting to highlight important data points and trends in the visualizations.
   - **Data Validation**  : Implemented data validation rules to ensure data quality and accuracy.
   - **Data Transformation** : Utilized Power Query Editor to perform data cleaning operations such as removing duplicates, filtering rows, and transforming data types.

## Data Analysis
Data Analysis involved exploring the sales data to answer key questions, such as:

  ## KPI's :
   1. Total Sales Analysis
   2. Total Order Analysis
   3. Total Quantity Sold Analysis

  ## Charts Requirements
   1. Calender Heat Map
   2. Sales Analysis by Weekdays/Weekends
   3. Sales Analysis by Store Location
   4. Daily Sales Analysis with Average Line
   5. Sales Analysis by Product category
   6. Top 10 Products by Sales
   7. Sales Analysis by Days and Hours

## Visualization Used in Power BI
 ### MySql & DAX
Utilized MySql and DAX to make measures and calculations for Total sales, Total orders, Total quantity sold, Sales analysis by weekdays and weekends, Sales analysis by store location, Daily sales with average line, Sales analysis by product category, Sales analysis by days and hours.

- **Total Sales Analysis** : Card and line chart to visualize total sales over different time periods.
- **Total Order Analysis** : Card and line chart to show the number of orders over different time periods.
- **Total Quantity Sold Analysis** : Card and line chart to display the total quantity of products sold.
- **Calendar map for monthly and daywise** : Matrix chart used to filter analysis based on month and day.
- **Sales Analysis by Weekdays and Weekends** : pie chart to compare sales on weekdays versus weekends.
- **Sales Analysis by Store Location** : Bar chart to show sales performance by location.
- **Daily Sales with Average Line** : Column chart with an average line to show daily sales trends.
- **Sales Analysis by Product Category** : Bar chart to display sales distribution across different product categories.
- **Top 10 Products by Sales** : Bar charts to highlight the top 10 products based on sales.
- **Sales Analysis by Days and Hours** : Matrix chart to analyze sales performance across different days and hours.
- 
- Tooltip in calender map and days & hours chart Implemented tooltip for the calendar map and matrix chart to display detailed information when hovering over each day and hour for analysis.


## Result
<img src = "https://github.com/user-attachments/assets/4bca7df0-6a52-4f3e-9582-a7ff9a682edc" width="900" height="600">

## Recommendations
- **Product Focus** : Prioritize top-selling items and address underperforming products.
- **Location Optimization** : Improve underperforming locations through targeted strategies.
- **Weekday/Weekend Promotions** : Tailor promotions to specific days.
- **Time-Based Marketing** : Optimize business hours and promotions based on sales patterns.
- **Customer-Centric Approach** : Understand customer preferences and adjust offerings accordingly.

## Conclusion
The Coffee Shop Sales Analysis dashboard provides valuable insights into the sales performance of the coffee shop. By understanding key metrics and trends, the company can make data-driven decisions to enhance sales strategies, improve product offerings, and optimize overall performance.










