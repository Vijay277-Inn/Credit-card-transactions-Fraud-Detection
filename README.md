Credit Card Analytics & Fraud Detection (SQL Project)

📌 Project Overview

This project focuses on credit card customer behavior analysis, risk detection, and fraud analytics using SQL.
The goal is to help a financial institution proactively identify fraud risks, understand spending behavior, and improve decision-making through data-driven insights.

The project uses synthetic but realistic transaction data and demonstrates advanced SQL querying skills, including window functions, CTEs, ranking, time-based analysis, and anomaly detection.

Business Problem Statement

How can a financial institution:

Identify high-risk customers and cards

Detect fraud patterns early

Understand customer lifetime value and behavior

Monitor security gaps (PIN inactivity, non-chip cards)

Improve credit exposure and operational efficiency

Data Model

The project uses normalized tables:

Table Name	Description
customers	Customer demographic and location details
transactions	Transaction-level data with fraud flag
merchants	Merchant category and location
cards_data	Card-level attributes (brand, type, chip, PIN, limits, expiry)

Key Analysis Sections

1️⃣ Customer Behavior & Spend Analytics

Monthly spend percentile per customer

Lifetime vs monthly spend comparison

Category seasonality detection

City-level rolling average spend

Cross-category spending shifts

Loyal merchant identification

Inactive cards & churn indicators

📈 Outcome:
Identifies stable vs abnormal spending, customer loyalty patterns, and early churn signals.


Fraud Analytics

Fraud rate per merchant

Fraud distribution by time of day

Repeat fraud customers

Pre-fraud spending behavior

Time gap between fraud & previous transaction

Fraud recurrence analysis

Merchant fraud concentration

🚨 Outcome:
Highlights high-risk merchants, customers, and time windows for real-time fraud prevention.


Credit Card Risk & Portfolio Insights

Average credit limit by card brand

Customers with expired or long-inactive PINs

Cards without chips

Dark web–flagged cards

High credit limit customers

Credit utilization ranking

Multiple card expiries in same year

Prepaid + Credit card combinations

Earliest adopters of cards

Average cards issued per client

🔐 Outcome:
Supports security hardening, compliance checks, and credit exposure management.


🧪 SQL Techniques Used

CTE (WITH clauses)

WINDOW FUNCTIONS (LAG, DENSE_RANK, NTILE)

DATE & TIME FUNCTIONS

PERCENTILE / RANKING

CASE WHEN logic

JOINs & SUBQUERIES

ANOMALY & THRESHOLD DETECTION


📊 Key Insights Summary

Customers hold ~3 cards on average, indicating strong cross-product adoption.

Thousands of cards have PINs unchanged for 10+ years, posing major security risks.

Chip vs non-chip cards have similar credit limits → strong case for full chip migration.

Fraud activity peaks during late-night hours (22:00–03:00).

Top customers generate massive value but require enhanced fraud protection.

Dark web–flagged cards demand immediate remediation.


🛠️ Tools & Technologies

SQL (Advanced)

BigQuery / MySQL-style SQL

Analytical & Fraud Detection Logic

Data Modeling & Business Insights


🎯 Use Cases

Fraud detection teams

Risk & compliance analysts

Credit portfolio managers

Data analyst interview case studies

SQL portfolio demonstration


📎 Notes

Dataset is synthetic and used for learning & demonstration.

Queries are optimized for clarity, correctness, and business interpretation.

Each query includes business insights, not just outputs.


