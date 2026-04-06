<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Churn Analysis - README</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.2.0/github-markdown.min.css">
    
    <style>
        body {
            background-color: #f6f8fa;
            margin: 0;
            padding: 20px;
        }
        .markdown-body {
            box-sizing: border-box;
            min-width: 200px;
            max-width: 980px;
            margin: 0 auto;
            padding: 45px;
            background: white;
            border: 1px solid #d0d7de;
            border-radius: 6px;
        }
        @media (max-width: 767px) {
            .markdown-body { padding: 15px; }
        }
    </style>
</head>
<body>

    <article id="content" class="markdown-body"></article>

    <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>

    <script>
        // Your README content in a variable
        const markdownContent = `
# 📊 Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)
![Power_BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

## 📌 Project Overview
This project analyzes customer churn to identify key factors that lead to customer loss and provides actionable insights to improve retention.

## 🎯 Objectives
* **Understand** why customers leave.
* **Identify** the most important churn drivers.
* **Business Goal:** Reduce churn, improve retention strategies, and minimize revenue loss.

---

## 📁 Dataset Description
The dataset contains **7,043 customers** and **21 features**, including demographics, services, account details, and churn status.

### 🧾 Feature Breakdown
| Category | Features |
| :--- | :--- |
| **Customer Info** | Gender, Senior Citizen, Partner, Dependents |
| **Account Info** | Tenure, Contract Type, Paperless Billing, Payment Method |
| **Services** | Phone, Internet (Fiber/DSL), Online Security, Tech Support, Streaming |
| **Charges** | Monthly Charges, Total Charges |
| **Target** | **Churn** (Yes/No) |

---

## 🛠️ Tools & Technologies
* **Language:** Python (Pandas, NumPy)
* **Database:** SQL
* **Visualization:** Power BI, Matplotlib/Seaborn

---

## 📊 Summary of Analysis

### 🔑 Key Insights
* **Churn Rate:** The overall churn rate is **26.58%**.
* **Contract Type:** Month-to-month contracts have a **42% churn rate**, while two-year contracts are only **3%**.
* **Service Impact:** Fiber optic users show higher churn compared to DSL users.

### 📈 Key Performance Indicators (KPIs)
| KPI | Value |
| :--- | :--- |
| **Overall Churn Rate** | 26.58% |
| **Monthly Recurring Revenue (MRR)** | $139,130.85 |
| **Avg. Tenure (Churned Users)** | 17.98 months |
| **Avg. Customer Lifetime Value (CLV)** | $1,531.80 |

---

## 💡 Recommendations
* **Incentivize Long-term Contracts:** Offer discounts to move month-to-month users to 1- or 2-year plans.
* **Service Bundling:** Focus on "sticky" service bundles to increase retention.

---

## 📬 Contact
* **Goda Saber**
* 📧 [godasaber6@gmail.com](mailto:godasaber6@gmail.com)
* 💼 [LinkedIn](https://www.linkedin.com/in/goda-saber-426532287/)
* 💻 [GitHub](https://github.com/GodaSaber)
        `;

        // 4. Render the Markdown into the HTML element
        document.getElementById('content').innerHTML = marked.parse(markdownContent);
    </script>

</body>
</html>
