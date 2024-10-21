# Transaction-Fraud-Detection-Analysis-Dashboard
Transaction Fraud Detection &amp; Analysis Dashboard

This repository contains SQL queries, DAX measures, and Power BI dashboards developed for detecting and analyzing suspicious and fraudulent activities in transaction data. The project is aimed at identifying anomalous transactions, fraud patterns across merchants, and summarizing suspicious transaction activities.

Project Overview
The project focuses on creating a comprehensive analysis of transaction data to detect fraudulent activities and anomalies. Using a blend of SQL, DAX, and Power BI, this solution analyzes key metrics related to transaction amounts, merchant fraud patterns, and suspicious customer activities.

Key Features:
SQL Data Modeling:

Data from 14 different tables was modeled, cleaned, and combined for detailed analysis.
Key tables: customer_data, account_activity, fraud_indicators, suspicious_activity, merchant_data, transaction_category_labels.
Power BI Dashboards:

Dashboard 1: Anomaly Detection in Transaction Amounts

Anomalies Transaction Trends (with a focus on 2023)
Merchant analysis for anomalous transactions (Merchant ID 2899 ranked 1)
Dashboard 2: Merchant Fraud Patterns

Fraudulent transactions by merchant category ("Other" category holds 21% of fraudulent activities)
Fraud indicators per merchant (Merchant ID 2701 ranked highest)
Dashboard 3: Suspicious Transaction Summary

Suspicious transactions summarized across categories and merchants (equal contributions across the board)
DAX Queries for Analysis:

Total Suspicious Transactions
Suspicious Transactions by Category
Fraudulent Transactions by Merchant Category
SQL Queries
You’ll find the SQL scripts used for data modeling and transformation, including:

Joins to link customer_data.csv and account_activity.csv based on CustomerID.
Cross join queries for linking merchant and transaction categories.
Calculations for identifying suspicious activities and fraud indicators.
DAX Measures
We used advanced DAX functions to calculate KPIs such as:

Total number of suspicious transactions
Total anomalous transactions
Fraudulent merchants by category and location
Power BI Dashboards
Visual insights include:

Anomalous transaction trends across time and merchants
Fraudulent patterns by merchant category and fraud indications
Suspicious transaction summary, offering an easy-to-understand view for business stakeholders
Conclusion
The project provides deep insights into transaction fraud detection and merchant fraud patterns. The results highlight areas where the company needs to focus more on anomaly detection, merchant fraud patterns, and suspicious transaction monitoring. Implementing stricter controls on high-risk merchants and refining fraud detection models are essential next steps for minimizing vulnerabilities.

