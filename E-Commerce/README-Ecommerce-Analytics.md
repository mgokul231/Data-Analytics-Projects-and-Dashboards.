# E-Commerce Sales & Customer Analytics Dashboard

## Overview
A 4-page interactive Power BI dashboard built on e-commerce transaction data — covering overall business performance, sales breakdowns, customer behavior, and trends over time. Data was cleaned and prepped in Python and Excel before being modeled and visualized in Power BI.

## Objective
Give a complete, drill-down view of the business — from a high-level summary down to customer-level and order-level detail — so decisions on regions, categories, payment methods, and delivery can be backed by data.

## Tools Used
- **Python** (Pandas) — data cleaning and preprocessing before loading into Power BI
- **Excel** — initial data checks and formatting
- **Power BI** — data modeling, DAX measures, Power Query, dashboard design

## Dataset Summary
- 7,903 customers, 34.50K orders, 51.43K units sold
- Total sales: ₹5.87M against a sales achievement target of ₹11.73M
- 7 product categories: Fashion, Electronics, Home, Toys, Sports, Beauty, Grocery
- 5 regions: North, South, East, West, Central
- 6 payment methods: Credit Card, Debit Card, COD, UPI, PayPal, Wallet
- Order data spans 2023–2025

## Pages in the Report

### 1. Overview
The landing page — total customers, total sales, total orders, and quantity sold at a glance, plus sales by payment method, sales by region, order counts by category, and monthly profit trend. Filterable by region, gender, returned status, and ordered year.

### 2. Sales Analysis
A detailed, order-level view — total price amount and shipping cost, a full order table (customer ID, age, year, region, quantity, shipping cost, price), and monthly profit split by customer gender. Filterable by product category, order date range, delivery time, and gender.

### 3. Customer Analysis
Customer-level breakdown — total customers, average customer age, a category-wise table of customer count/sales/profit, sales by payment method, returns by gender, monthly profit trend, and quarterly sales-vs-profit comparison. Filterable by gender, product category, returned status, and month.

### 4. Trend Analysis
Time-based and operational trends — average delivery time, sales achievement vs. target (gauge), order count by category, monthly profit, monthly quantity trend, and monthly sales amount trend. Filterable by region, delivery time, order date range, and quarter.

## Key Skills Demonstrated
- Data cleaning and preparation with Python/Pandas
- Multi-page dashboard design with consistent navigation
- DAX measures for KPIs, targets, and time-intelligence (monthly/quarterly trends)
- Customer segmentation and returns analysis
- Sales achievement tracking against targets
- Cross-filtering and interactive slicers across regions, categories, gender, and dates

## Files
- Power BI report (`.pbix`)
- Python scripts used for data cleaning (if included in repo)
- Source Excel/CSV data files
