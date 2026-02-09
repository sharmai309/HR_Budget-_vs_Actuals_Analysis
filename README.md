# Julius AI – Budget vs Actuals Analysis
## Overview
This repository documents my hands-on work using Julius AI to perform budget vs actuals analysis and answer finance and business questions using natural language prompts. The project demonstrates how AI-assisted analytics can accelerate exploratory data analysis, variance calculation, and insight generation without extensive manual coding.
Julius AI was used as an interactive data analysis environment to load CSV data, compute key financial variances, and summarize findings in a clear, decision-focused manner.Consider a typical budget vs actuals dataset containing monthly expenses across departments, with a detailed breakdown of HR-related costs such as salaries, hiring, benefits, and training.

## Objective
The main objectives of this project are:
1.To analyze budget vs actual financial performance
2.To compute revenue, expense, and net profit variances
3.To demonstrate how GenAI-powered tools like Julius AI can support financial analysis and reporting
4.To translate raw data into actionable business insights

## Dataset
File: budget_vs_actuals_10000_rows.csv
## Content:
1. Budgeted revenue and expenses
2. Actual revenue and expenses
3. Derived variance metrics
4. The dataset simulates realistic financial reporting data with sufficient scale for meaningful analysis.

## Analysis Performed
Using Julius AI, the following analyses were conducted:
### 1. Revenue Budget Variance
Definition:
actual_revenue − budget_revenue
Positive variance indicates favorable performance (revenue exceeded budget)

### 2. Expense Budget Variance
Definition:
budget_expense − actual_expense
Positive variance indicates favorable performance (spend below budget)

### 3. Net Budget Variance (Profit Variance)
Definition:
(actual_revenue − actual_expense) − (budget_revenue − budget_expense)
Measures overall profitability performance vs budget
Julius AI was used to compute aggregates, summarize results, and generate visualizations to support interpretation.

## Tools & Technologies
Julius AI – AI-driven data analysis platform
Python (executed within Julius AI environment)
Pandas – data manipulation and aggregation
CSV-based financial data

## Key Insights

Revenue performance showed a favorable variance
Expenses exceeded budget, resulting in an unfavorable expense variance
Overall profitability was unfavorable, driven primarily by cost overruns rather than revenue shortfalls
This highlights how expense control, not revenue generation, was the primary driver of underperformance.

## Why Julius AI?

Julius AI enables analysts to:
Ask natural language questions over datasets
Rapidly compute KPIs and variances
Reduce time spent on boilerplate code

## Author

### Isha Sharma
### Data Scientist – Risk, Fraud & Financial Analytics
https://julius.ai/s/notebooks/07adb022-4060-4a14-879f-7e18638065a9?utm_source=share&utm_campaign=notebooks&utm_medium=referral

Focus more on interpretation and decision-making

This project demonstrates how GenAI tools can complement traditional data science workflows rather than replace them.
