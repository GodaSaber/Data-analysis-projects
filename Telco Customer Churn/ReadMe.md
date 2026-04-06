<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Churn Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f9f9f9;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        hr {
            border: 1px solid #ccc;
            margin: 20px 0;
        }
        ul, ol {
            margin: 10px 0 20px 20px;
        }
        table {
            border-collapse: collapse;
            width: 100%;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #ccc;
        }
        th {
            background-color: #f2f2f2;
            text-align: left;
        }
        th, td {
            padding: 10px;
        }
        img {
            display: block;
            margin: 20px 0;
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<h1>📊 Customer Churn Analysis</h1>

<h2>📌 Project Overview</h2>
<p>
This project analyzes customer churn to identify key factors that lead to customer loss and provides actionable insights to improve retention.
</p>

<hr>

<h2>🎯 Objective</h2>
<ul>
    <li>Understand why customers leave</li>
    <li>Identify the most important churn drivers</li>
</ul>

<hr>

<h2>💼 Business Goal</h2>
<ul>
    <li>Reduce customer churn</li>
    <li>Improve retention strategies</li>
    <li>Minimize revenue loss</li>
</ul>

<hr>

<h2>📁 Dataset Description</h2>
<p>
The dataset contains <b>7,043 customers</b> and <b>21 features</b>, including demographics, services, account details, and churn status.
</p>

<hr>

<h2>🧾 Features</h2>

<h3>🔹 Customer Information</h3>
<ul>
    <li><b>customerID</b> – Unique identifier</li>
    <li><b>gender</b> – Male / Female</li>
    <li><b>SeniorCitizen</b> – 1 = Yes, 0 = No</li>
    <li><b>Partner</b> – Yes / No</li>
    <li><b>Dependents</b> – Yes / No</li>
</ul>

<h3>🔹 Account Information</h3>
<ul>
    <li><b>tenure</b> – Months with the company</li>
    <li><b>Contract</b> – Month-to-month, One year, Two year</li>
    <li><b>PaperlessBilling</b> – Yes / No</li>
    <li><b>PaymentMethod</b> – Payment type</li>
</ul>

<h3>🔹 Services Subscribed</h3>
<ul>
    <li>PhoneService</li>
    <li>MultipleLines</li>
    <li>InternetService (DSL, Fiber optic, No)</li>
    <li>OnlineSecurity</li>
    <li>OnlineBackup</li>
    <li>DeviceProtection</li>
    <li>TechSupport</li>
    <li>StreamingTV</li>
    <li>StreamingMovies</li>
</ul>

<h3>🔹 Charges</h3>
<ul>
    <li>MonthlyCharges</li>
    <li>TotalCharges</li>
</ul>

<h3>🔹 Target Variable</h3>
<ul>
    <li><b>Churn</b> – Yes / No</li>
</ul>

<hr>

<h2>🛠️ Tools & Technologies</h2>
<ul>
    <li>Python (Pandas, NumPy)</li>
    <li>SQL</li>
    <li>Power BI</li>
    <li>Excel</li>
</ul>

<hr>

<h2>🔍 Data Analysis Process</h2>
<ol>
    <li>Data Cleaning</li>
    <li>Exploratory Data Analysis (EDA)</li>
    <li>Data Visualization</li>
    <li>Churn Factor Analysis</li>
    <li>Dashboard Creation</li>
</ol>

<hr>

<h2>📊 Summary of Analysis</h2>

<h3>🔑 Key Insights</h3>
<ul>
    <li>Overall churn rate is <b>26.58%</b> (~1 in 4 customers leave)</li>
    <li><b>Month-to-month contracts</b> have the highest churn (<b>42%</b>) vs <b>3%</b> for two-year contracts</li>
    <li>Higher monthly charges → higher churn</li>
    <li>Longer tenure → lower churn</li>
    <li>Customers with partners/dependents churn less</li>
    <li>Senior customers and paperless billing users churn more</li>
    <li>Customers without internet service churn less</li>
    <li>Fiber optic users show higher churn</li>
    <li>Customers with multiple services are more likely to stay</li>
</ul>

<h3>📈 Key Performance Indicators (KPIs)</h3>
<table>
    <tr>
        <th>KPI</th>
        <th>Value</th>
    </tr>
    <tr>
        <td>Overall Churn Rate</td>
        <td>26.58%</td>
    </tr>
    <tr>
        <td>Monthly Recurring Revenue (MRR)</td>
        <td>$139,130.85</td>
    </tr>
    <tr>
        <td>Avg. Tenure (Churned Customers)</td>
        <td>17.98 months</td>
    </tr>
    <tr>
        <td>Churn Rate (Two-Year Contract)</td>
        <td>3%</td>
    </tr>
    <tr>
        <td>Churn Rate (Month-to-Month)</td>
        <td>42%</td>
    </tr>
    <tr>
        <td>Avg. Customer Lifetime Value (CLV)</td>
        <td>$1,531.80</td>
    </tr>
</table>

<h3>📊 Visual Insights</h3>
<ul>
    <li>Pie charts show customer distribution across services and payment methods</li>
    <li>Stacked bar charts show churn concentrated in:
        <ul>
            <li>Month-to-month contracts</li>
            <li>Customers with fewer services</li>
        </ul>
    </li>
</ul>

<hr>

<h2>💡 Conclusions & Recommendations</h2>
<ul>
    <li>High-risk customers: <b>month-to-month + high charges</b></li>
    <li>Offer <b>long-term contract incentives</b></li>
    <li>Provide <b>bundled services</b> to increase retention</li>
    <li>Focus on <b>fiber optic users</b> and <b>senior customers</b></li>
</ul>

<hr>

<h2>📊 Dashboard</h2>
<p>Power BI dashboard includes:</p>
<ul>
    <li>Churn rate tracking</li>
    <li>Customer segmentation</li>
    <li>KPI monitoring</li>
</ul>

<!-- <img src="dashboard.png" alt="Dashboard" width="700"> -->

<hr>

<h2>🚀 Conclusion</h2>
<p>
This project provides data-driven insights to understand customer churn and helps businesses improve retention strategies.
</p>

<hr>

<h2>📬 Contact</h2>
<ul>
    <li>📧 Email: <a href="mailto:godasaber6@gmail.com">godasaber6@gmail.com</a></li>
    <li>💼 LinkedIn: <a href="https://www.linkedin.com/in/goda-saber-426532287/" target="_blank">Goda Saber</a></li>
    <li>💻 GitHub: <a href="https://github.com/GodaSaber" target="_blank">GodaSaber</a></li>
</ul>

</body>
</html>
