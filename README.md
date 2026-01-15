# Customer Churn & Revenue Analysis – Data Analyst Project

## Overview
This project analyzes customer churn and revenue patterns for a subscription-based business using Python. The goal is to identify key churn drivers, understand customer segments, and provide actionable business recommendations to improve customer retention and revenue.

## Business Problem
Customer churn directly impacts revenue and growth. This analysis helps answer:
- Which customers are most likely to churn?
- What factors contribute to churn?
- Which customer segments generate the highest revenue?
- How can the business reduce churn and increase customer lifetime value?

## Dataset
Telco Customer Churn Dataset  
Source: Kaggle – blastchar/telco-customer-churn

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## Project Structure
daxwell-churn-analysis/
│
├── data/
│ └── customer_data.csv
├── notebooks/
│ └── churn_analysis.ipynb
├── visuals/
│ ├── churn_distribution.png
│ └── churn_by_contract.png
├── README.md
└── requirements.txt

## Steps Performed
1. Data loading and inspection  
2. Data cleaning and type conversion  
3. Feature engineering (Revenue calculation)  
4. KPI calculation (Churn rate, average tenure, revenue)  
5. Exploratory Data Analysis (EDA)  
6. Visualization of churn trends  
7. Business insights and recommendations  

## Key Insights
- Month-to-month contract customers have the highest churn rate.
- Customers with higher monthly charges are more likely to churn.
- Long-term contracts (1 year, 2 year) show significantly lower churn and higher average revenue.

## Business Recommendations
- Incentivize customers to move from month-to-month to long-term contracts.
- Identify high monthly charge customers early and target them with retention campaigns.
- Improve onboarding and support experience for new customers to reduce early churn.
- Bundle services to increase customer value and reduce churn risk.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook

