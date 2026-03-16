# Swetha
coding challenge1
Sales Data Analysis using Excel
Project Overview
This project analyzes a sales dataset using Microsoft Excel.
The goal is to clean the data, calculate total revenue, and generate insights using Pivot Tables and charts.
Dataset Description
The dataset contains the following columns:
Order_ID – Unique identifier for each order
Order_Date – Date of the order
Region – Sales region (East, West, North, South)
Product – Product name
Category – Product category
Quantity – Number of units sold
Unit_Price – Price per unit
Data Cleaning Process
The following steps were performed to clean the dataset:
Adjusted column width to fix date display issues (######).
Converted Order_Date column to proper date format.
Checked and removed duplicate Order_ID values.
Trimmed extra spaces in text columns.
Ensured numeric columns (Quantity and Unit_Price) were correctly formatted.
Revenue Calculation
A new column Total_Revenue was created using the formula:
=F2*G2
This multiplies Quantity × Unit Price for each order.
To calculate the total revenue of the entire dataset, the following formula was used:
=SUMPRODUCT(F2:F47, G2:G47)
Data Analysis Using Pivot Tables
1. Revenue by Region
Pivot Table configuration:
Rows: Region
Values: Sum of Total_Revenue
This analysis shows which region generates the highest revenue.
2. Revenue by Category
Pivot Table configuration:
Rows: Category
Values: Sum of Total_Revenue
This identifies the most profitable product categories.
3. Top Performing Products
To find the Top 5 products by revenue:
Create a Pivot Table.
Add Product to Rows.
Add Total_Revenue to Values.
Apply Value Filters → Top 5 based on Sum of Total_Revenue.
Data Visualization
A Column Chart was created to visualize Revenue by Region.
Steps:
Create Pivot Table with Region and Total_Revenue.
Select the Pivot Table.
Insert → Column Chart → Clustered Column Chart.
This chart helps quickly identify the highest performing region.
Tools Used
Microsoft Excel
Pivot Tables
Excel Charts
Data Cleaning Functions
Key Insights
Identified the regions generating the highest revenue.
Determined top-performing product categories.
Found the top five products based on sales revenue.
Conclusion
This project demonstrates basic data cleaning, analysis, and visualization techniques in Excel.
It provides valuable insights into sales performance and helps in data-driven decision-making.
