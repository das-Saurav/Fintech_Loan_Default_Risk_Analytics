# 📊 Fintech Loan Default Risk Analytics — End-to-End Data Analytics Project

Domain: Fintech • Credit Risk • Loan Analytics
Tech Stack: Python, Pandas, NumPy, Matplotlib, Seaborn, SQL, Power BI

# 📌 Project Overview

This project analyzes a synthetic (but realistic) fintech loan dataset containing customer demographics, credit behavior, repayment performance, and risk indicators.
The goal is to build a complete data analytics workflow including:

✔ Data Cleaning
✔ Feature Engineering
✔ Exploratory Data Analysis (EDA)
✔ Risk segmentation
✔ Dashboarding (Power BI)
✔ Business insights for credit decisioning

# 🗂️ Dataset Features

The dataset contains fields such as
Customer Data: age, gender, income, employment_type, city, state
Loan Details: loan_amount, issue_date, interest_rate, term_months, monthly_emi
Risk & Performance: credit_score, risk_score, previous_defaults, overdue_days
Repayments: payments_made, recovery_amount, collection_attempts
Target Variable: status (Current / Default)

Data includes ~1% intentional missing values to simulate real-world fintech conditions.

# 🔧 Data Cleaning & Preprocessing

Performed using Python (Pandas):
Handling missing values (median/mode imputation)
Date parsing & corrections
Duplicate removal
Standardizing numerical & categorical types

# 🔍 Feature Engineering

Created financial & risk-related features:
EMI-to-Income Ratio
Affordability Score
Loan Age (days)
Risk Buckets (High/Medium/Low)
PAR30 / PAR60 / PAR90 delinquency flags
Total Payable Amount
Remaining Balance

These features improve model explainability and mimic real credit analytics workflows.

# 📈 Exploratory Data Analysis (EDA)

Analyzed:
Default vs income distribution
Credit score impact on repayment
Risk-based customer segmentation
State/city-wise loan performance
Recovery efficiency analysis
EMI burden & affordability trends

Visualized using Matplotlib + Seaborn.

# 📊 Power BI Dashboard

Interactive dashboard includes:
Portfolio overview
Default rate & high-risk segments
Recovery performance
Collections effectiveness
State/city-level borrower insights
Credit score & risk distribution

# 🧠 Key Insights

High EMI-to-Income Ratio strongly correlates with defaults
Credit score < 600 group shows 3× higher overdue rates
Previous defaults are the strongest predictor of delinquency
Some cities/states exhibit disproportionately higher risk
High-risk borrowers tend to have higher collection attempts but lower recovery
