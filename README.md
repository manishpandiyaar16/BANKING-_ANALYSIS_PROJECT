# Banking Risk Analytics Dashboard

End-to-end Data Analytics project focused on **Risk Analytics in Banking & Financial Services**.

The goal of this project is to help banks make better lending decisions by analyzing client profiles, loan exposure, deposit patterns, and engagement behavior using data.

---

## 📌 Project Overview

Banks face challenges in assessing the creditworthiness of clients. Incorrect lending decisions can lead to higher risk and financial losses.  

This project analyzes banking client data to identify patterns that support risk evaluation and smarter lending decisions.

**Tools Used:**  
Python (Pandas, Seaborn) | MySQL | Power BI (DAX)

---

## 📂 Dataset

- Banking client data covering:
  - Loans
  - Deposits
  - Credit Cards
  - Business Lending
  - Client demographics & engagement

---

## 🔍 What I Did

### 1. Data Cleaning & EDA (Python)
- Loaded and cleaned banking client data
- Handled data consistency and validation
- Performed Exploratory Data Analysis
- Identified correlations between different account types

### 2. Data Storage & Analysis (MySQL)
- Loaded cleaned data into MySQL
- Structured the data for further analysis and reporting

### 3. Interactive Dashboard (Power BI)
Built a Power BI dashboard with key banking KPIs using DAX measures such as:
- `SUMX`
- `DISTINCTCOUNT`
- `DATEDIFF`
- `SWITCH`

**Key Metrics Tracked:**
- Total Clients
- Total Loan
- Total Deposit
- Business Lending
- Credit Card Balance
- Client Engagement Length

---

## 📊 Key Insights

- Strong positive correlation between **Bank Deposits**, **Checking Accounts**, and **Saving Accounts**
- Business Lending forms a major portion of the total loan portfolio
- High Income Band clients contribute a significant share of both loans and deposits
- Clear patterns visible across gender, nationality, occupation, and engagement length

---

## 💡 Business Recommendations

- Monitor high concentration of loans and deposits in the High Income segment
- Identify clients with multi-product relationships (higher engagement)
- Use engagement length and account patterns as supporting indicators for risk assessment
- Focus on balanced portfolio distribution to 
