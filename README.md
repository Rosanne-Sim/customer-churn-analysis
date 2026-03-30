# Customer Churn Analysis

## Objective

This project analyses customer churn behaviour in a telecom company to identify key factors driving customer attrition and provide actionable business recommendations.

---

## Tools Used

* SQL (SQLite via Jupyter Notebook)
* Python (Pandas)
* Jupyter Notebook

---

## Dataset

The dataset contains customer-level information including demographics, service usage, contract type, tenure, and billing details.

* **Churn** indicates whether a customer has discontinued their service (Yes/No).

---

## Key Analyses

### 1. Overall Churn Rate

Approximately **26.5% of customers have churned**, indicating a significant customer retention issue.

---

### 2. Churn by Contract Type

* Month-to-month contracts: **42.7% churn rate**
* One-year contracts: **11.3% churn rate**
* Two-year contracts: **2.8% churn rate**

**Insight:** Customers on shorter-term contracts are significantly more likely to churn.

---

### 3. Churn by Tenure

* New customers (≤12 months): **47.4% churn rate**
* Mid-term customers (13–36 months): **25.5% churn rate**
* Long-term customers (37+ months): **11.9% churn rate**

**Insight:** Churn is highest in the early stages of the customer lifecycle.

---

### 4. Monthly Charges and Churn

* Churned customers: **$74.44 average monthly charges**
* Retained customers: **$61.27 average monthly charges**

**Insight:** Higher monthly charges are associated with increased likelihood of churn, suggesting price sensitivity.

---

## Key Findings

Customer churn is primarily driven by three factors:

* **Contract Structure** → Short-term contracts increase churn risk
* **Customer Tenure** → New customers are the most vulnerable
* **Pricing Levels** → Higher charges correlate with higher churn

---

## Business Recommendations

* Encourage customers to switch to **long-term contracts** through incentives
* Strengthen **onboarding and early engagement** for new customers
* Review **pricing strategies** and provide value-added services for high-paying customers

---

## Project Files

* `customer_churn_analysis_sql.ipynb` → Full analysis and SQL queries
* `Telco-Customer-Churn.csv` → Dataset
