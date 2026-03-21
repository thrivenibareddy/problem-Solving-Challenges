# 📊 Financial Overview Dashboard (Power BI)

## 🚀 Project Overview

This project focuses on analyzing **customer behavior, transactions, and loan performance** in the banking sector using **Power BI**.

The goal is to transform raw banking data into **meaningful insights** through data cleaning, modeling, and interactive visualizations.


## 📁 Dataset Information

### 🔑 Key Columns:

* `Customer_ID` – Unique identifier for each customer
* `Customer_Name` – Customer’s full name
* `Age` – Customer age
* `Gender` – Male / Female
* `Account_Type` – Savings, Current, Fixed Deposit, Loan
* `Balance` – Current account balance
* `Transaction_Date` – Date of transaction
* `Transaction_Type` – Credit / Debit
* `Transaction_Amount` – Transaction value
* `Loan_Status` – Active, Closed, Default


## 🧹 Data Cleaning & Transformation

Performed using **Power Query**:

* Removed duplicate records
* Handled missing values
* Created **Net Transaction Impact** column
* Grouped customers into **Age Categories**
* Standardized account types (SAV, CUR, FD, LN)
* Created **Date-based columns**:

  * Month
  * Day Name


## 🧠 Data Modeling

* Built relationships between tables using `Customer_ID`
* Created a **Calendar Table** for time-based analysis
* Established proper date hierarchy (Year → Month → Day)


## 📏 DAX Measures

Key metrics created:

* 💰 Total Deposits
* 💸 Total Withdrawals
* 📈 Net Balance Growth
* 📊 Average Account Balance
* ⚠️ Loan Default Rate (%)
* 📅 Monthly Transaction Volume
* 💡 Customer Profitability Score


## 📊 Dashboard Features

### 🔹 Customer Overview

* Total Customers KPI
* Customers by Age Group & Gender


### 🔹 Transaction Analysis

* Monthly transaction trends (Line Chart)
* Transactions by Day of Week
* Transactions by Customer (Top contributors)

### 🔹 Interactive Filters (Slicers)

* Gender
* Account Type
* Loan Status


## 🔥 Key Insights

* Credit vs Debit trends reveal customer spending behavior
* Majority of transactions occur on weekdays
* Certain customers contribute significantly to transaction volume
* Loan default rate highlights potential financial risk

## 🛠 Tools & Technologies

* **Power BI** (Data Visualization)
* **Power Query** (Data Transformation)
* **DAX** (Data Analysis Expressions)


## 📸 Dashboard Preview
<img width="1168" height="677" alt="image" src="https://github.com/user-attachments/assets/61eece7d-6c63-4895-a53f-277a4661628d" />








Give this repo a ⭐ and share your feedback!

