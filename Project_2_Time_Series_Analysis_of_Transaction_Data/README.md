# Project 2: Time-Series Analysis of Transaction Data

## Project Overview
This project focuses on time-series analysis of transaction data spanning multiple years. The objective is to identify long-term trends, seasonal behavior, and temporal patterns in transaction amounts.

## Dataset Description
The dataset contains transaction-level records with the following key fields:
- Datetime of transaction
- Transaction amount
- Transaction number

The dataset includes partial-year data for some years, reflecting realistic data collection constraints.
- Source: Kaggle
- Rows: 83488
- Columns: 3

## Objectives
- Convert and handle datetime data correctly
- Engineer time-based features such as year and month
- Analyze year-wise and month-wise transaction behavior
- Visualize trends while maintaining data integrity

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib

## Key Analysis Performed
- Datetime conversion and chronological sorting
- Extraction of year and month features
- Year-wise aggregation of transaction amounts
- Month-wise seasonality analysis across all years
- Combined year–month analysis using multi-index groupby
- Visualization with corrected axis formatting and annotations

## Handling of Missing Data
The dataset contains incomplete monthly data for certain years (e.g., missing months in 2017). These missing months were intentionally retained as NaN values rather than being filled with zeros to preserve the true structure and availability of the data.

## Key Insights
- Year-wise Trend: Transactions grow steadily from 2013 to 2016, indicating long-term growth, while 2017 shows a sharp decline, likely due to incomplete or abnormal data.
- Monthly Seasonality: Transaction activity peaks between March and July, with July as the highest month, reflecting strong mid-year demand.
- Low Activity Period: Transactions decline from September to December, highlighting a consistent end-of-year slowdown.
- Partial-year data highlights the importance of cautious interpretation in time-series analysis

## Conclusion
This project demonstrates practical time-series analysis using real-world transactional data. By prioritizing correct datetime handling, ethical treatment of missing values, and clear visual communication, the project showcases how meaningful insights can be derived even from minimal datasets.

The analysis lays the groundwork for more advanced techniques such as rolling averages, anomaly detection, and forecasting.