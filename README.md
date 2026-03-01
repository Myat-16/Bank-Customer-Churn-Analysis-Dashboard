# 🏦 Bank Customer Churn Analysis

## 📌 Project Overview
This project analyzes **customer churn behavior** in a retail banking dataset.  
The goal is to identify **key drivers of churn**, evaluate customer risk profiles, and provide actionable insights for retention strategies.

---

## 📊 Data Source
- **Dataset:** Maven Data Analytics – Bank Customer Churn Dataset  
- **File:** `Bank_Churn.csv`  

---

## 💡 Key Business Impacts
- **Customer Retention:** Understanding churn drivers helps design targeted retention campaigns.  
- **Revenue Protection:** Identifying high-risk customers reduces potential revenue loss.  
- **Product Strategy:** Linking product ownership to churn guides cross-sell and upsell opportunities.  
- **Risk Management:** Monitoring credit score distributions supports proactive risk mitigation.  
- **Operational Efficiency:** Analyzing tenure and activity levels informs loyalty programs and customer engagement strategies.  

---

## 🔍 Approaches & Analysis
- **High-Level KPIs:** Total customers, total balance, churn rate, CLV proxy, demographics, credit score distribution.  
- **Operational Insights:** Active customers, product ownership, risk monitoring, tenure analysis, churn by activity and geography.  
- **Predictive Modeling:** Random Forest Classifier using `Balance`, `NumOfProducts`, and `Tenure` to predict churn.  

---

## 🗂️ Dataset Columns Used
- CustomerId  
- CreditScore  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- NumOfProducts  
- IsActiveMember  
- Exited  

---

## 🧹 Data Cleaning
- Checked for missing values  
- Standardized formats  
- Created **RiskLevel categories** based on credit score thresholds  

---

## 📈 Tools & Libraries
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Predictive modeling  

---

## 📊 Results & Insights
- **Overall churn rate:** ~20% of customers exited.  
- **Tenure impact:** Churned customers had **shorter average tenure** compared to retained ones.  
- **Active membership:** Inactive members showed **higher churn rates**.  
- **Product ownership:** Customers with only **1 product** were more likely to churn.  
- **Risk profile:** Customers with **credit scores < 600** were classified as high risk.  
- **Model performance:** The Random Forest classifier achieved reasonable accuracy in predicting churn patterns.  

---

## 🚀 Business Applications
- Targeted retention campaigns for **high-risk and single-product customers**  
- Loyalty programs to reward **long-tenure active members**  
- Regional strategies for **geography-specific churn patterns**  
- Risk monitoring dashboards for **credit score distributions**

<img width="570" height="431" alt="Screenshot 2026-03-01 234905" src="https://github.com/user-attachments/assets/c8c46bc9-745f-4ea7-8b6e-1210d0d741c4" />

<img width="549" height="433" alt="Screenshot 2026-03-01 234951" src="https://github.com/user-attachments/assets/134852ae-d8ac-4431-8737-52c9b4ba1778" />

<img width="542" height="430" alt="Screenshot 2026-03-01 235105" src="https://github.com/user-attachments/assets/033e8c4e-14ab-424c-8438-4709e3a1645c" />




