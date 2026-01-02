# Project 3- Customer Purchase Behavior & Churn Analysis

## Project Overview
This project analyzes customer transaction data to understand purchasing behavior, segment customers based on spending patterns, and examine churn characteristics. The goal is to derive actionable business insights using exploratory data analysis and rule-based segmentation.

This project is designed to reflect real-world customer analytics tasks commonly required in data analytics and freelancing roles.

---

## Dataset Description
The dataset contains transactional and customer-level information with the following key fields:

- Customer ID
- Customer Name
- Age
- Gender
- Purchase Date
- Product Category
- Product Price
- Quantity
- Total Purchase Amount
- Payment Method
- Returns (0 = No return, 1 = Return)
- Churn (0 = Retained, 1 = Churned)

- Source: Kaggle
- Rows: 250000
- Columns: 13
  

## Objectives
- Analyze overall customer purchasing behavior
- Perform customer-level aggregation
- Segment customers based on total spending
- Compare churned vs retained customer behavior
- Generate business-relevant insights from data

---

## Data Cleaning & Preparation
- Removed duplicated or redundant columns (e.g., duplicate age fields)
- Handled missing values in the returns column by assuming no return where data was absent
- Converted data types for consistency and analysis readiness
- Extracted time-based features from purchase dates where required

---

## Feature Engineering
Customer-level metrics were created using aggregation:
- Total amount spent per customer
- Total number of orders per customer
- Average order value

These features formed the foundation for segmentation and churn analysis.

---

## Customer Segmentation Logic
Customers were segmented into three groups using spending quantiles:

- *Low Value Customers* – Bottom 33% of total spend
- *Medium Value Customers* – Middle 33% of total spend
- *High Value Customers* – Top 33% of total spend

This rule-based segmentation ensures interpretability and balanced group sizes.

---

## Key Insights

### 1. Customer Spending Behavior and Churn
- The average total spending, order frequency, and average order value are remarkably similar between churned and retained customers.
- This indicates that churn in this dataset is *not strongly driven by spending intensity alone*.
- High spenders are just as likely to churn as lower spenders, suggesting that factors beyond monetary value influence customer retention.

### 2. Customer Segment Distribution
- Customers are evenly distributed across Low, Medium, and High Value segments.
- This balanced segmentation confirms the effectiveness of the quantile-based approach and ensures that comparisons across segments are statistically meaningful.

### 3. Churn Is Not Solely a Revenue Issue
- Since churned customers exhibit comparable spending patterns to retained customers, revenue-based targeting alone may be insufficient for retention strategies.
- Behavioral and experiential factors such as returns, product satisfaction, or payment experience may play a more significant role.

### 4. Interpretability of Rule-Based Segmentation
- The rule-based segmentation approach provides clear and explainable customer groups.
- This method enables business stakeholders to easily understand and act upon the results without relying on complex models.

---

## Conclusion
The analysis highlights that customer churn cannot be explained solely by spending patterns. While segmentation provides a clear understanding of customer value tiers, retention strategies should incorporate behavioral and experiential factors beyond revenue.

This project demonstrates practical skills in data cleaning, aggregation, segmentation, and business-oriented insight generation, making it suitable for real-world analytics and freelancing applications.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Status
Completed