Retail Sales Performance Dashboard
Overview

This project demonstrates how Power BI and SQL Server can be used to analyze retail sales data and turn it into actionable business insights. The dashboard was built using data stored in the RealAnalyticsDemo SQL Server database and provides a simple way to monitor sales performance, customer activity, and product trends.

The goal of this project was to create a reporting solution that allows users to quickly identify top-performing products, sales trends, customer purchasing behavior, and key business metrics through interactive visualizations.

Technologies Used
Power BI
Microsoft SQL Server
SQL Server Management Studio (SSMS)
T-SQL
Database

Data for this project comes from the RealAnalyticsDemo database.

Main tables include:

Customers
Products
Orders
OrderItems
Payments
Dashboard Features
Sales Overview
Total Revenue
Total Orders
Average Order Value
Monthly Sales Trends
Product Performance
Top Selling Products
Revenue by Product
Product Sales Distribution
Customer Analysis
Top Customers by Revenue
Customer Purchase Activity
Order Frequency
Regional Performance
Revenue by Region
Sales Comparison Across Regions
Key Business Questions

This dashboard helps answer questions such as:

Which products generate the most revenue?
Which customers contribute the highest sales volume?
How are sales trending over time?
Which regions perform the best?
What is the average value of a customer order?
Project Structure

RetailSalesPerformanceDashboard/

├── RealAnalyticsDemo.sql

├── RetailSalesDashboard.pbix

├── Screenshots/

│ ├── DashboardOverview.png

│ ├── ProductPerformance.png

│ └── CustomerAnalysis.png

└── README.md

How to Run
Restore or execute the RealAnalyticsDemo.sql script in SQL Server.
Open RetailSalesDashboard.pbix in Power BI Desktop.
Update the SQL Server connection if necessary.
Refresh the dataset.
Explore the dashboard.
What I Learned

This project provided hands-on experience with:

SQL data extraction and analysis
Data modeling
Power BI dashboard development
Business intelligence reporting
Data visualization best practices
Future Enhancements
Profitability analysis
Inventory tracking
Forecasting and trend analysis
Additional customer segmentation metrics
Automated data refresh processes