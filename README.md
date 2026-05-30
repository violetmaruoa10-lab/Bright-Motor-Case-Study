# Bright-Motor-Case-Study
Project Overview

This project analyses historical vehicle sales data for Bright Motors to provide insights that can help improve sales performance, profitability, and decision-making. Databricks SQL was used for data cleaning and analysis, while Microsoft Excel was used for visualisation and dashboard creation.

Business Objective

The analysis aimed to identify:

Top-performing car makes and models
Revenue and profitability trends
Regional sales performance
Relationships between vehicle age, mileage, and selling price
Customer purchasing patterns over time
Dataset Description

The dataset contains vehicle sales transactions, including information on vehicle make, model, year, transmission, condition, mileage, location, market value (MMR), selling price, and sale date.

Data Cleaning & Transformation

The following steps were performed:

Converted numeric fields to appropriate data types
Converted sale date text into timestamp format
Standardised text fields for consistency
Checked for missing values and duplicates
Created additional analytical columns

Calculated Fields
Total Revenue = Selling Price × Units Sold
Profit = Selling Price − MMR
Profit Margin = ((Selling Price − MMR) ÷ Selling Price) × 100
Vehicle Age
Mileage Bucket
Price Category
Performance Tier
Time Bucket
Analysis Conducted
Revenue by Month
Profit Margin by Month
Revenue by State
Revenue by Vehicle Make and Model
Sales by Time Bucket
Vehicle Age vs Selling Price
Mileage Bucket Analysis
Performance Tier Distribution
Price Category Distribution

Tools Used
Databricks SQL
Microsoft Excel (Pivot Tables & Charts)
Microsoft PowerPoint

Key Assumptions
Each row represents one vehicle sold
MMR was used as a proxy for market value when estimating profit
State was used as the regional indicator
Fuel type analysis was excluded as fuel type data was not available

Conclusion

The project transformed raw vehicle sales data into actionable business insights, highlighting key revenue drivers, profitability trends, customer purchasing behaviour, and regional performance to support future business decisions at Bright Motors.
