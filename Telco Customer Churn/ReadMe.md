# Project: Customer Churn Analysis

## Objective
Analyze customer churn and identify the key factors that contribute to customer loss.

## Business Goal
Reduce customer churn and minimize revenue loss.

---

## 📁 Data Description

The dataset contains **7,043 customers** and **21 features**, including:

- Demographic information
- Subscribed services
- Account details
- Churn status

### 🔹 Customer Information

- **customerID**: Unique customer identifier
- **gender**: Customer gender (`Male` / `Female`)
- **SeniorCitizen**: Whether the customer is a senior citizen (`1 = Yes`, `0 = No`)
- **Partner**: Whether the customer has a partner (`Yes` / `No`)
- **Dependents**: Whether the customer has dependents (`Yes` / `No`)

### 🔹 Account Information

- **tenure**: Number of months the customer has stayed with the company
- **Contract**: Contract type (`Month-to-month`, `One year`, `Two year`)
- **PaperlessBilling**: Whether the customer uses paperless billing (`Yes` / `No`)
- **PaymentMethod**: Customer’s payment method

### 🔹 Services Subscribed

- **PhoneService**: Whether the customer has phone service
- **MultipleLines**: Whether the customer has multiple lines
- **InternetService**: Type of internet service (`DSL`, `Fiber optic`, `No`)
- **OnlineSecurity**: Whether the customer has online security
- **OnlineBackup**: Whether the customer has online backup
- **DeviceProtection**: Whether the customer has device protection
- **TechSupport**: Whether the customer has tech support
- **StreamingTV**: Whether the customer uses streaming TV
- **StreamingMovies**: Whether the customer uses streaming movies

### 🔹 Charges

- **MonthlyCharges**: Monthly amount charged to the customer
- **TotalCharges**: Total amount charged to the customer

### 🔹 Target Variable

- **Churn**: Whether the customer left the company (`Yes` / `No`)

---

## Summary of Analysis

### 1. Key Insights

- The overall churn rate is **26.58%**, meaning about one in four customers leave the service.
- Customers with **month-to-month contracts** have the highest churn rate at **42%**.
- Customers with **two-year contracts** have a much lower churn rate of only **3%**.
- **Higher monthly charges** are associated with increased churn.
- **Longer tenure** significantly reduces the likelihood of churn.
- Customers with **partners or dependents** tend to stay longer.
- **Senior citizens** and customers using **paperless billing** show higher churn behavior.
- Customers with **no internet service** are less likely to churn.
- Customers using **fiber optic internet** exhibit higher churn rates.
- Customers subscribed to **multiple services** such as online security, backup, and streaming are more likely to stay.

---

### 2. Key Performance Indicators (KPIs)

| KPI | Value |
|-----|-------|
| Overall Churn Rate | 26.58% |
| Monthly Recurring Revenue (MRR) | \$139,130.85 |
| Average Tenure of Churned Customers | 17.98 months |
| Churn Rate (Two-Year Contract) | 3% |
| Churn Rate (Month-to-Month Contract) | 42% |
| Average Customer Lifetime Value (CLV) | \$1,531.80 |

---

### 3. Visual Insights

- **Pie charts** illustrate the distribution of customers across different services and payment methods.
- **Stacked bar charts** show that churn is heavily concentrated among:
  - Customers with **month-to-month contracts**
  - Customers with **fewer subscribed services**

---

### 4. Conclusions & Recommendations

- Customers on **month-to-month contracts** and those with **higher monthly charges** are at the highest risk of churn.
- Introducing **long-term contract incentives** could significantly reduce churn.
- Offering **bundled services** and **loyalty programs** may improve customer retention.
- Special attention should be given to **fiber optic users** and **senior customers**, as they represent high-risk customer segments.

---

## Final Takeaway

This analysis highlights the major drivers of customer churn and provides actionable business recommendations to improve retention. By targeting high-risk groups and encouraging long-term engagement, the company can reduce churn and protect recurring revenue.
