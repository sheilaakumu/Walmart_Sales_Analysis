# Walmart_Sales_Analysis
This repository contains a project for analyzing sales data using MySQL to gain valuable insights into sales performance, customer behavior, and product performance.
The dataset includes information on sales transactions, such as invoice details, branch locations, customer types, product lines, prices, quantities sold, and more.

# Dataset Features
invoice_id: Invoice of the sales made (VARCHAR(30))
branch: Branch at which sales were made (VARCHAR(5))
city: The location of the branch (VARCHAR(30))
customer_type: The type of the customer (VARCHAR(30))
gender: Gender of the customer making purchase (VARCHAR(10))
product_line: Product line of the product sold (VARCHAR(100))
unit_price: The price of each product (DECIMAL(10, 2))
quantity: The amount of the product sold (INT)
VAT: The amount of tax on the purchase (FLOAT(6, 4))
total: The total cost of the purchase (DECIMAL(10, 2))
date: The date on which the purchase was made (DATE)
time: The time at which the purchase was made (TIMESTAMP)
payment_method: The method of payment (VARCHAR(30))
cogs: Cost Of Goods Sold (DECIMAL(10, 2))
gross_margin_percentage: Gross margin percentage (FLOAT(11, 9))
gross_income: Gross Income (DECIMAL(10, 2))
rating: Rating (FLOAT(2, 1))

# Analysis Questions
-- Total Sales by Branch
-- Monthly Sales Trends
-- Average Unit Price by Product Line
-- Sales Distribution by Customer Type
-- Gender-wise Sales Analysis
-- Top Performing Cities
-- Peak Sales Hours
-- Average Rating by Product Line
-- Gross Income by Branch
-- Profitability Analysis
-- Sales Performance Over Time
-- Payment Methods Analysis
-- Cost of Goods Sold (COGS) by Product Line
-- VAT Contribution
-- Sales Quantity Analysis
