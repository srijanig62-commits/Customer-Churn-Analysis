# Customer Churn Analysis 📉

## Project Overview
This project focuses on analyzing customer churn to understand key factors influencing customer retention and churn behavior. The analysis is performed using Python with Pandas, Matplotlib, and Seaborn, and visualized through multiple plots.

---

## Dataset Overview
- Total Customers: **7,043**
- Churn = No: **5,174 customers (73.46%)**
- Churn = Yes: **1,869 customers (26.54%)**

This indicates that approximately **1 out of every 4 customers churned**, highlighting a significant retention challenge.

---

## Key Insights from Exploratory Data Analysis

### 1. Overall Churn Distribution
- **73.46%** of customers did not churn
- **26.54%** of customers churned

---

### 2. Churn by Senior Citizen
- Non-senior customers show **lower churn counts**
- Senior citizens exhibit a **higher proportion of churn**, indicating age-related retention risk

---

### 3. Churn by Gender
- Churn distribution is **almost equal for male and female customers**
- Gender does **not appear to be a strong churn driver**

---

### 4. Churn by Tenure
- Customers with **shorter tenure** have a **higher churn rate**
- Long-tenure customers are significantly more likely to stay
- Correlation with churn: **–0.35**

---

### 5. Churn by Monthly Charges
- Customers who churn generally have **higher monthly charges**
- Median monthly charge for churned customers is noticeably higher
- Correlation with churn: **+0.19**

---

### 6. Churn by Contract Type
- **Month-to-month contracts** have the **highest churn**
- **One-year and two-year contracts** show much better retention

---

### 7. Churn by Payment Method
- Customers using **electronic check** show higher churn
- Auto-payment methods (credit card / bank transfer) show lower churn

---

### 8. Correlation Analysis
Key correlations with churn:
- Tenure: **–0.35**
- Monthly Charges: **+0.19**
- Paperless Billing: **+0.19**
- Partner: **–0.15**
- Dependents: **–0.16**

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Conclusion
Customer churn is strongly influenced by **contract type, tenure, and monthly charges**. Customers on short-term contracts with higher charges and shorter tenure are at the highest risk of churning.

---

