<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
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
        const markdownContent = `
# 📊 Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)
![Power_BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

## 📌 Project Overview
This project analyzes customer churn to identify key factors that lead to customer loss and provides actionable insights to improve retention.

## 📊 Summary of Analysis
* **Churn Rate:** The overall churn rate is **26.58%**.
* **Contract Type:** Month-to-month contracts have a **42% churn rate**.

| KPI | Value |
| :--- | :--- |
| **Overall Churn Rate** | 26.58% |
| **Avg. CLV** | $1,531.80 |

## 📬 Contact
* **Goda Saber**
* 📧 [godasaber6@gmail.com](mailto:godasaber6@gmail.com)
        `;

        // This line tells the browser: "Take the text above and turn it into a visual page"
        document.getElementById('content').innerHTML = marked.parse(markdownContent);
    </script>

</body>
</html>
