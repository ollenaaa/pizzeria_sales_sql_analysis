# Pizzeria Sales Analysis with SQL

## Goal
This project focuses on SQL analysis of a pizza sales dataset.
The main goal is to demonstrate proficiency in SQL by writing queries of varying complexity, performing data transformations, and extracting business insights directly from a PostgreSQL database.

## Project Overwiev
This analysis examines pizza sales data from 2015 to identify operational patterns, optimize menu efficiency, and provide actionable business recommendations. The project combines SQL queries with Python visualizations

## Database Structure
### Source: https://mavenanalytics.io/data-playground/pizza-place-sales
The database consists of 4 main tables:
<img width="914" height="753" alt="image" src="https://github.com/user-attachments/assets/623b8a7f-f90e-4180-bc61-69b5eb3c9519" />

## Functions and techniques
- Window Functions (ROW_NUMBER, PARTITION BY)
- CTE (WITH)
- Conditional Logic (CASE WHEN)
- Type Casting (::DATE, ::INTEGER)
- String Processing (STRING_TO_ARRAY, UNNEST, TRIM)
- Multiple Table Joins (INNER, LEFT)
- Date/Time Functions (EXTRACT)
- Aggregations (GROUP BY, SUM, COUNT, AVG)

## Next steps
While the analysis yielded insights into aggregated transaction data—order times, pizza types, and total sales—without customer-level tracking. This prevents essential capabilities including customer lifetime value calculation, churn rate measurement, retention campaign targeting, and personalized marketing. The business cannot distinguish loyal repeat customers from one-time buyers, making it impossible to optimize acquisition versus retention spending or deploy predictive churn prevention strategies.
