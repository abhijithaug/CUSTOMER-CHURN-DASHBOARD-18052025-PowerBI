# CUSTOMER-CHURN-DASHBOARD-18052025-PowerBI

## 📌 Overview

The **Customer Churn Dashboard** is an interactive Power BI solution designed to help businesses understand **why customers are leaving (churning)** and identify patterns that lead to customer attrition. By visualizing data around demographics, services, tenure, billing, and support issues, this dashboard offers actionable insights to reduce churn and retain high-value customers.


---

## ⭐ Key Performance Indicators (KPIs)

| KPI                      | Description |
|--------------------------|-------------|
| **Total Customers**      | Total number of customers in the dataset |
| **Churned Customers**    | Number of customers who left the service |
| **Churn Rate (%)**       | Percentage of customers who churned |
| **Total Monthly Charges**| Combined monthly charges from all customers |
| **Total Charges**        | Total amount paid by all customers |
| **Revenue Lost**         | Total revenue lost due to churned customers |
| **Senior Churn Rate**    | Churn rate among senior citizens |
| **Admin/Tech Tickets**   | Count and percentage of admin vs tech support tickets |

---

## 📊 Visualizations Explained

### 1. **Churn Count vs Contract Type**
   - Highlights churn behavior across contract lengths (Month-to-month vs Yearly)
   - **Insight**: Customers with month-to-month contracts are more likely to churn.

### 2. **Churn by Gender**
   - Donut chart showing churn distribution between male and female customers.
   - **Insight**: Gender impact is minimal—churn is balanced.

### 3. **Churn Rate by Payment Method**
   - Clustered bar chart visualizing churn count per payment type.
   - **Insight**: Customers using manual payments churn more.

### 4. **Churn by Tenure Group**
   - Bar chart that categorizes customers based on how long they've stayed.
   - **Insight**: New customers (<12 months) churn more frequently.

### 5. **Internet Service and Churn**
   - Donut and horizontal bar charts showing churn rate across internet service types.
   - **Insight**: Fiber optic users churn more, indicating possible dissatisfaction.

### 6. **Churn vs Charges and Contract**
   - Line chart comparing monthly charges and churn across contract types.
   - **Insight**: Higher charges under flexible contracts increase churn risk.

### 7. **Tech Support and Churn**
   - Bar chart comparing churn based on tech support availability.
   - **Insight**: Customers without tech support are more likely to leave.

---

## 🧠 Insights Uncovered

- Customers with **shorter contracts** (month-to-month) are significantly more likely to churn.
- **New customers** within their first year show a high churn rate, suggesting onboarding or early engagement gaps.
- **Senior citizens** show a higher churn rate, indicating a potential need for personalized support.
- **Fiber optic internet users** churn more frequently—possibly due to quality or cost concerns.
- Lack of **Tech Support** is a strong churn predictor.
- **Manual payment methods** like mailed checks have higher churn than automatic payments.

---

## 🔧 Power BI Tools Used

- **Power BI Desktop** for data modeling and visualization
- **Power Query** for data transformation (e.g., tenure grouping, calculated columns)
- **DAX Measures** for KPIs and calculated metrics

---
