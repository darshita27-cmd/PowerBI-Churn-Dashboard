# 📊 Customer Churn Analysis - Power BI Dashboard

This repository contains a Power BI dashboard project that analyzes customer churn using a sample **Bank Customer Dataset**. The visualizations are designed to identify trends and patterns contributing to customer churn, offering insights for retention strategies.

## 🔍 Project Overview

**Objective:**  
To analyze bank customer churn data and derive meaningful insights into factors influencing churn behavior such as tenure, contract type, internet services, and payment methods.

**Tools Used:**
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Sample Dataset: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

## 📈 Dashboard Features

The dashboard includes the following visual components:

- **KPI Cards**
  - Total Customers
  - Active Customers
  - Churn Rate

- **Line Chart:**  
  - Tenure vs Average Monthly Charges & Average Total Charges

- **Bar Charts:**  
  - Sum of Total Charges by Tenure
  - Number of Customers & Churn Rate by Tenure

- **Pie / Donut Charts:**  
  - Customers by Internet Services
  - Customers by Contract Type
  - Customers by Gender
  - Customers by Payment Method

- **Churn Filter:**  
  - Toggle between Churned and Non-Churned customers for deep drill-down analysis

## 📂 Dataset

The dataset used in this project contains the following fields:
- `customerID`
- `gender`
- `SeniorCitizen`
- `Partner`
- `Dependents`
- `tenure`
- `PhoneService`
- `MultipleLines`
- `InternetService`
- `OnlineSecurity`, `OnlineBackup`, etc.
- `Contract`, `PaperlessBilling`, `PaymentMethod`
- `MonthlyCharges`, `TotalCharges`
- `Churn` (Target column)

📌 **Source:** Public Telco Customer Churn dataset

## ✅ Key Insights

- Churn rate is extremely high (~3612% calculated on filtered sample).
- Customers with short tenure tend to churn more.
- Monthly and total charges have a visible impact on customer retention.
- Fiber optic users show higher churn compared to DSL users.
- Customers with monthly contracts are more likely to churn than those on long-term contracts.

## 🧠 How to Use

1. Download the `.pbix` file.
2. Open it using Power BI Desktop.
3. Use the slicers to filter data and interact with the visuals.
4. Modify or extend the dashboard as needed for your use case.

## 📌 Project Status

✅ Initial version completed  
🔄 Future Improvements:
- Add predictive churn scoring using Power BI and Python integration
- Enable real-time updates through streaming data

