# 📊 PhonePe Transaction Analytics Dashboard
## 🚀 Project Overview
The PhonePe Transaction Analytics Dashboard is a comprehensive Power BI Business Intelligence solution designed to analyze digital payment transactions, customer behavior, service performance, and growth trends.
This project transforms raw transaction data into actionable insights that support strategic decision-making for fintech organizations.
## Business Goal
To analyze transaction patterns, user engagement, service performance, and platform reliability to uncover growth opportunities and improve business performance.
## DataSet Used
<a href="https://github.com/nikhilsingh7874-alt/phonepe-transaction-analytics-dashboard/blob/main/Phonepe-Final-Dataset.xlsx">Phonepe-Final-Dataset.xlsx</a>
  
## Dashboard Created
<a href="https://github.com/nikhilsingh7874-alt/phonepe-transaction-analytics-dashboard/blob/main/PhonePe_Analysis.pdf">View Dashboard</a>
## 🎯 Business Problems Solved
✔ Understanding transaction growth patterns 

✔ Identifying high-value customer segments

✔ Evaluating service performance

✔ Tracking user engagement

✔ Monitoring transaction success rates

✔ Analyzing weekday vs weekend behavior

✔ Improving business decision-making through data-driven insights

## 🛠 Tech Stack
| Tool          | Purpose               |
| ------------- | --------------------- |
| Power BI      | Dashboard Development |
| SQL           | Data Extraction       |
| Excel         | Data Cleaning         |
| DAX           | KPI Calculations      |
| Power Query   | ETL Process           |
| Data Modeling | Star Schema Design    |

## 📈 Key KPIs

Total Transactions 300K+

Total Transaction Value ₹3.47 Billion


Active Users 108K+

Transaction Success Rate 96%

## 📊 Dashboard Insights

💰 Loans Drive Revenue

₹2.5 Billion transaction value

71.8% of service value contribution

👥 Customer Segmentation

Millennials: 37.58%

Gen X: 37.07%

Gen Z: 20.78%


📅 Weekday Dominance

71.6% transactions occur on weekdays

2.5x higher than weekends

📈 Platform Growth

8.97% MoM transaction growth

8.98% MoM value growth

These insights summarize the strongest trends identified in the analysis.

## 📚 DAX Measures Used

Total Transactions =
SUM(Transactions[Transaction_Count])

Total Transaction Amount =
SUM(Transactions[Transaction_Amount])

Average Transaction Value =
DIVIDE(
    [Total Transaction Amount],
    [Total Transactions]
)

Monthly Growth % =
DIVIDE(
    [Current Month Transactions] -
    [Previous Month Transactions],
    [Previous Month Transactions]
)

Running Total =
CALCULATE(
    [Total Transactions],
    FILTER(
        ALLSELECTED(DateTable),
        DateTable[Date] <= MAX(DateTable[Date])
    )
)

##🎯 Business Impact

1.Improved strategic decision-making

2.Enhanced customer understanding

3.Revenue optimization opportunities

4.Operational efficiency improvements

5.Better resource planning

6.Stronger fintech business intelligence capabilities

These outcomes are highlighted in the project's impact assessment

##🌟 Author

Nikhil Singh

📊 Data Analyst | Power BI Developer | SQL Enthusiast

🔗 LinkedIn: Add Your LinkedIn URL https://www.linkedin.com/in/nikhil-singh-48a676327?utm_source=share_via&utm_content=profile&utm_medium=member_android
