
# 🏦 Banking Dashboard Analysis

[![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)](https://powerbi.microsoft.com/)
[![Python](https://img.shields.io/badge/Language-Python-blue?logo=python)](https://www.python.org/)
[![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-red?logo=microsoftsqlserver)](https://www.microsoft.com/en-us/sql-server)

An **interactive Power BI dashboard** for analyzing **banking operations** including loans, deposits, client demographics, and financial performance.  
Built with **Python (ETL)** → **MS SQL Server (storage)** → **Power BI (visualization)**.  

---

## 📁 Dataset Features  

The dataset `bankingdataset.csv` contains:  

- **Client Info:** `Client ID`, `Name`, `Age`, `GenderId`, `AgeGroup`, `Income Band`, `Nationality`, `Occupation`  
- **Banking Relationship:** `Joined Bank`, `Banking Contact`, `Loyalty Classification`, `BRId`, `IAId`  
- **Financials:**  
  - Loans & Credit → `Bank Loans`, `Business Lending`, `Credit Card Balance`, `Amount of Credit Cards`  
  - Deposits & Accounts → `Bank Deposits`, `Checking Accounts`, `Saving Accounts`, `Foreign Currency Account`  
  - Assets & Savings → `Properties Owned`, `Superannuation Savings`, `Estimated Income`, `Fee Structure`  
- **Risk:** `Risk Weighting`  

---

## 🧠 Objectives  

- 📊 Track and analyze **loan distribution** across demographics  
- 💰 Understand **deposit patterns** based on nationality & occupation  
- 📈 Monitor **loan-to-deposit ratios** for financial stability  
- 🎯 Provide **interactive filtering** for deeper insights  

---

## 🔧 Tools & Tech Stack  

- **Python** → Data Cleaning & Transformation  
- **MS SQL Server** → Data Integration & Storage  
- **Power BI** → Dashboarding & Insights  
- **DAX** → Custom Calculations  

---

## 📊 Dashboard Pages  

<details>
<summary>1️⃣ Home Page</summary>  

- **Total Clients:** 3000  
- **Total Loan:** ₹4.38B  
- **Checking Accounts:** ₹963.28M  
- **Saving Accounts:** ₹698.73M  
- **Business Lending:** ₹2.60B  

</details>  

<details>
<summary>2️⃣ Loan Analysis</summary>  

- **Total Loan:** ₹2.19B  
  - Bank Loans → ₹876.24M  
  - Business Lending → ₹1.31B  
  - Credit Card Balance → ₹4.80M  
- **By Income Band (Pie):**  
  - Medium → ₹456.92M (52.15%)  
  - Low → ₹232.86M (26%)  
  - High → ₹186.46M (21.8%)  
- **By Relationship:** Private (₹7.3M), Institutional (₹2.7M)  
- **By Occupation:** Highest = ₹9.7M  

</details>  

<details>
<summary>3️⃣ Deposit Analysis</summary>  

- **Total Deposits:** ₹1.90B  
  - Bank Deposits → ₹1.02B  
  - Checking Accounts → ₹488.37M  
- **By Nationality:**  
  - Asian → ₹4.5M  
  - European → ₹0.9M  
- **By Occupation:** Varied contribution  

</details>  

<details>
<summary>4️⃣ Summary</summary>  

- **Loan-to-Deposit Ratio:** 88%  
- Quick comparative KPIs for decision-making  

</details>  

---

## 📌 Key Insights  

- ✅ Medium-income clients dominate **loan distribution (52%)**  
- ✅ **Asian clients** hold the highest deposits, Europeans the lowest  
- ✅ Private & Institutional banking have relatively **lower loan volumes**  
- ✅ **Loan-to-Deposit ratio at 88%** shows strong lending activity  

---

## 🚀 How to Run  

1. **Preprocess Data** with Python scripts  
2. Load into **MS SQL Server**  
3. Connect Power BI → SQL Server  
4. Open `.pbix` file  
5. Explore with slicers (gender, occupation, banking relationship, etc.)  

---

## 📷 Screenshots  

> *(Add visuals of each dashboard page here for better presentation)*  

---

## 📂 Project Structure  

```

📦 Banking-Dashboard
┣ 📜 bankingdataset.csv
┣ 📜 BankingDashboard.pbix
┣ 📜 data_cleaning.py
┣ 📜 README.md

```

---

## ⭐ Acknowledgements  

This project was developed as part of **Banking Data Analytics** exploration using **Power BI**.  
Special focus on **client demographics, risk analysis, and financial ratios** for business insights.  

---
