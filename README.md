# coffee-sales-analysis
Excel-based sales analysis &amp; dashboard


# ☕ Coffee Sales Analysis – Vending Machine
## 📌 Project Overview

This project analyzes coffee sales data from a vending machine to understand sales performance, customer behavior, and payment trends.
The analysis was conducted end-to-end using Microsoft Excel, from data cleaning to dashboard visualization.

The goal of this project is to demonstrate my ability to:
* Clean and transform raw data
* Define meaningful business KPIs
* Build a clear and professional dashboard
* Translate data into actionable business insights

## 🗂 Dataset

* Source: Kaggle – Coffee Sales Dataset
* Data Type: Transaction-level sales data
* Granularity: 1 row = 1 transaction

### Key Fields:
* Transaction Date & Time
* Product
* Payment Method (Card / Cash)
* Card ID (for repeat customer analysis)
* Price / Revenue

⚠️ Note: The dataset does not provide a native transaction ID, therefore a transaction ID was created based on row number.

## 🔄 Data Analysis Workflow

Data Source
→ Data Cleaning
→ Feature Engineering
→ KPI Calculation
→ Dashboard Visualization
→ Business Insight & Recommendation

All steps were performed using Microsoft Excel.


### 🧹 Data Cleaning

The following data preparation steps were performed:
* Removed empty and invalid rows
* Standardized date and time formats
* Handled missing customer identifiers
* Identified cash transactions (card_id = "-")
* Trimmed text fields to avoid duplication issues

### 🧩 Feature Engineering

Several derived fields were created to support analysis:
* **Transaction ID** – generated using row number
* **Month** – extracted from transaction date for trend analysis
* **Hour** – extracted from transaction time for peak hour analysis
* **Is_Repeat** – classified transactions as Repeat / Single / Cash
* **Revenue** – calculated per transaction

### 📊 Key Metrics (KPIs)

The dashboard focuses on the following business KPIs:
* Total Revenue
* Total Transactions
* Average Order Value (AOV)
* Repeat Customer Rate (Calculated based on card transactions only)

### 📈 Dashboard Overview

The Excel dashboard provides a high-level business summary including:
* Monthly revenue trend
* Revenue contribution by product
* Peak transaction hours
* Payment method distribution
* Key performance indicators (KPI cards)

📸 (**Dashboard Preview:**)


### 💡 Key Insights

Some key insights derived from the analysis:
* A small number of products contribute the majority of revenue
* Most transactions occur during morning to mid-day hours
* Card payments dominate transactions, indicating low reliance on cash
* Repeat customers contribute a significant share of card transactions

### 🧠 Business Recommendations

Based on the findings:
* Prioritize inventory and maintenance during peak hours
* Focus promotions on high-revenue products
* Encourage card-based payments to support loyalty programs
* Consider operational optimization based on transaction timing

## ⚠️ Data Limitations

* Cash transactions cannot be linked to individual customers
* No customer demographic data available
* No promotion or pricing change information provided

## 🛠 Tools Used

### Microsoft Excel
* Data Cleaning
* Pivot Tables
* KPI Calculations
* Dashboard Design

# 👤 Author

**AGUSTIANTO**

Aspiring Data Analyst

📍 Indonesia

🔗 LinkedIn: [link LinkedIn]

🔗 GitHub: [link GitHub]

## ⭐ Final Notes

This project is part of my data analytics portfolio and demonstrates my ability to perform business-oriented analysis using Excel.

Feedback and suggestions are welcome.
