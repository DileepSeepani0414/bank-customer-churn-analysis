# 📊 Banklytics – Customer Churn Analysis Dashboard

## 📌 Project Overview

Banklytics is an end-to-end Power BI project focused on analyzing **customer churn behavior** in a banking dataset.

This project helps identify:

* Why customers leave
* Which segments are at risk
* How business can improve retention

---

## 🖼️ Dashboard Snapshots

### 🔹 Customer Overview

<img width="1284" height="728" alt="image" src="https://github.com/user-attachments/assets/d6eab608-e51f-4a2e-a232-06660dacd3b2" />



### 🔹 Churn Analysis

<img width="1284" height="726" alt="image" src="https://github.com/user-attachments/assets/203e543b-10b7-4d87-b5fc-365929631055" />


### 🔹 Product & Credit Analysis

<img width="1286" height="727" alt="image" src="https://github.com/user-attachments/assets/b941df8e-0cbc-4a28-9c3c-49dfbef40ffd" />


---

## 📂 Project Structure

```id="struc2"
Banklytics-Churn-Analysis
│
├── Churn Dataset
│   ├── ActiveCustomer.xlsx
│   ├── Bank_Churn.xlsx
│   ├── CreditCard.xlsx
│   ├── CustomerInfo.xlsx
│   ├── ExitCustomer.xlsx
│   ├── Gender.xlsx
│   └── Geography.xlsx
│
├── Report
│   ├── Banklytics Dashboard.pbix
│ 
└── README.md
```

---

## 📊 Key Metrics (From Dashboard)

* 👥 **Total Customers:** 10,000
* ❌ **Exited Customers:** 2,037
* ✅ **Retained Customers:** 7,963
* 📈 **Retention Rate:** 79.63%
* 💰 **Average Balance:** 76.49K
* 💼 **Average Salary:** 100.09K

---

## 📊 Detailed Insights

### 👤 Customer Demographics

* Male Customers: **53.67% (2318)**
* Female Customers: **46.33% (2001)**
* Majority belong to **Middle-Aged segment (~3376 customers)**

---

### 🌍 Geography Insights

* 🇩🇪 Germany: **Highest churn rate (~8.14%)**
* 🇫🇷 France: **~8.10% churn rate**
* 🇪🇸 Spain: **Lowest churn (~4.13%)**

---

### 📉 Churn Behavior

* Customers with **1 product → Highest exit rate (~14.09%)**
* Customers with **more products → Lower churn**
* Inactive customers are more likely to churn

---

### 💳 Credit Card Insights

* Credit Card Holders: **70.55% (7.06K)**
* Non-holders: **29.45% (2.95K)**
* Card holders show **better retention behavior**

---

### ⚡ Activity Insights

* Active Customers: **5088**
* Inactive Customers: **4912**
* Exit rate higher among **inactive users**

---

## ⚙️ Tech Stack

* Power BI Desktop
* Power Query
* Excel
* DAX

---

## 🔄 Data Processing Workflow

### 🟠 Data Collection

* Imported multiple Excel files containing structured customer data

### 🟠 Data Cleaning

* Removed nulls & duplicates
* Standardized columns
* Created derived fields (Age Group, Tenure Category)

### 🟠 Data Modeling

* Built relationships across tables
* Implemented star schema approach

### 🟠 DAX Measures

* Total Customers
* Exited Customers
* Retention %
* Avg Balance & Salary
* Active vs Inactive

---

## 🎯 Business Impact

This dashboard enables:

* Identification of high-risk churn customers
* Region-wise performance analysis
* Product optimization strategies
* Improved customer retention planning

---
