# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to identify purchasing trends, customer segments, product preferences, and factors influencing customer decisions to support data-driven business strategies.

The project combines Python, SQL, and Power BI to perform data cleaning, analysis, visualization, and business intelligence reporting.

---

## Business Problem

A retail company wants to better understand customer shopping behavior to improve sales performance, customer satisfaction, and long-term loyalty.

### Business Question

**How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

## Dataset Information

### Dataset Summary

* Total Records: 3,900
* Total Features: 18
* Data Type: Customer Shopping Transactions

### Key Attributes

* Customer ID
* Age
* Gender
* Location
* Subscription Status
* Item Purchased
* Category
* Purchase Amount
* Season
* Discount Applied
* Previous Purchases
* Review Rating
* Shipping Type
* Frequency of Purchases

---

## Project Architecture

### 1. Data Preparation (Python)

Tasks performed:

* Loaded dataset using Pandas
* Performed exploratory data analysis
* Handled missing values in Review Rating
* Standardized column names
* Created age group categories
* Generated additional analytical features
* Exported cleaned data for database analysis

### Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* PostgreSQL Connector

---

### 2. Data Analysis (SQL)

Business-focused SQL queries were created to answer key stakeholder questions.

#### Analysis Performed

* Revenue by Gender
* High-Spending Discount Users
* Top Rated Products
* Shipping Type Comparison
* Subscriber vs Non-Subscriber Analysis
* Discount Dependency Analysis
* Customer Segmentation
* Revenue by Age Group
* Top Products by Category
* Repeat Buyer Analysis

---

### 3. Dashboard Development (Power BI)

An interactive dashboard was built to visualize customer purchasing patterns and business insights.

#### Dashboard Features

* Revenue Overview
* Customer Demographics
* Product Performance
* Subscription Analysis
* Shipping Analysis
* Customer Segmentation
* Purchase Behavior Trends

---

## Key Insights

### Revenue Analysis

* Female customers generated slightly higher revenue than male customers.

### Customer Loyalty

* Subscribers showed higher average spending and stronger retention behavior.

### Shipping Behavior

* Express shipping customers spent more per transaction than standard shipping customers.

### Product Performance

* Highly rated products demonstrated strong customer satisfaction and purchase frequency.

### Customer Segmentation

Customers were categorized into:

* New Customers
* Returning Customers
* Loyal Customers

---

## Business Recommendations

### Increase Subscription Adoption

Offer exclusive member benefits and personalized promotions to encourage subscriptions.

### Improve Customer Retention

Implement loyalty programs and reward repeat purchases.

### Optimize Discount Strategy

Use discounts strategically to maximize revenue while maintaining profit margins.

### Promote High-Performing Products

Feature top-rated and best-selling products in marketing campaigns.

### Target High-Value Segments

Focus marketing efforts on customer groups contributing the highest revenue.

---

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── reports/
│   ├── Customer Shopping Behavior Analysis.pdf
│   └── Business Problem Document.pdf
│
├── presentation/
│   └── Customer-Shopping-Behavior-Analysis.pptx
│
└── README.md
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* PostgreSQL
* SQL
* Power BI
* Git
* GitHub

---

## Learning Outcomes

Through this project, the following skills were developed:

* Data Cleaning and Transformation
* Exploratory Data Analysis (EDA)
* SQL Query Development
* Business Intelligence Reporting
* Dashboard Design
* Customer Segmentation Analysis
* Data-Driven Decision Making

---

## Author

Harsh Katoch

Customer Shopping Behavior Analysis Project

Developed as an end-to-end Data Analytics project using Python, SQL, and Power BI.
