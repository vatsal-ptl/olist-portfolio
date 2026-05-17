\# Olist E-Commerce SQL Analysis



\## Overview

SQL analysis of the Olist Brazilian E-Commerce dataset (Kaggle) 

containing 100,000+ orders across 8 relational tables. 

All queries written in MySQL 8.0.



\## Business Questions Answered

1\. Total revenue and orders by status

2\. Top 10 product categories by revenue

3\. Customer distribution by state with % of total

4\. Top 10 sellers by revenue

5\. Underperforming categories by average payment value

6\. Most popular payment methods

7\. Category revenue rank and % of total

8\. Month-over-month revenue change

9\. Top 2 sellers per category

10\. Customer retention — 2017 vs 2018



\## Key Findings

\- 97% of revenue comes from delivered orders across 96k transactions

\- Health \& beauty leads all categories at $1.26M revenue

\- São Paulo state accounts for 42% of all customers

\- Platform retention rate is 0.65% — growth driven entirely by new customers

\- Revenue grew 9x through 2017, plateauing around $1M/month in 2018



\## Skills Used

\- Multi-table JOINs (2–4 tables)

\- CTEs (single, chained, cross-joined)

\- Window Functions: RANK(), LAG(), SUM OVER()

\- Aggregations: SUM, COUNT DISTINCT, AVG

\- Date functions: DATE\_FORMAT, YEAR



\## Tools

\- MySQL 8.0

\- MySQL Workbench

\- Dataset: \[Olist Brazilian E-Commerce — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

