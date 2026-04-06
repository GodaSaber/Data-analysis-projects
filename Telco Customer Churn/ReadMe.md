<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Churn Analysis | Report</title>
    <style>
        /* Modern CSS Reset & Variables */
        :root {
            --primary-dark: #2c3e50;
            --accent-blue: #3498db;
            --bg-light: #f8f9fa;
            --text-main: #333;
            --shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-light);
            margin: 0;
            padding: 40px 20px;
            line-height: 1.6;
            color: var(--text-main);
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        /* Typography */
        h1 {
            color: var(--primary-dark);
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 40px;
            border-bottom: 4px solid var(--accent-blue);
            display: inline-block;
            width: 100%;
            padding-bottom: 10px;
        }

        h2 {
            color: var(--primary-dark);
            font-size: 1.5rem;
            margin-top: 0;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        h3 {
            color: var(--accent-blue);
            font-size: 1.1rem;
            margin-top: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Card Style */
        section {
            background-color: #fff;
            padding: 30px;
            margin-bottom: 30px;
            border-radius: 12px;
            box-shadow: var(--shadow);
            transition: transform 0.2s ease;
        }

        section:hover {
            transform: translateY(-5px);
        }

        /* Table Styling */
        .table-container {
            overflow-x: auto;
        }

        table {
            border-collapse: collapse;
            width: 100%;
            margin: 20px 0;
            border-radius: 8px;
            overflow: hidden;
        }

        th, td {
            text-align: left;
            padding: 15px;
            border-bottom: 1px solid #eee;
        }

        th {
            background-color: var(--primary-dark);
            color: #fff;
            font-weight: 600;
        }

        tr:nth-child(even) {
            background-color: #fcfcfc;
        }

        tr:hover {
            background-color: #f1f7ff;
        }

        /* Lists & Links */
        ul, ol {
            padding-left: 20px;
        }

        li {
            margin-bottom: 10px;
        }

        b {
            color: var(--accent-blue);
        }

        a {
            color: var(--accent-blue);
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Badge Style for Features */
        .feature-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            list-style: none;
            padding: 0;
        }

        .feature-list li {
            background: #e1ecf4;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            color: var(--primary-dark);
        }

        .footer-section {
            text-align: center;
            background: var(--primary-dark) !important;
            color: white;
        }

        .footer-section h2, .footer-section a {
            color: white;
        }

        @media (max-width: 600px) {
            body { padding: 20px 10px; }
            section { padding: 20px; }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>📊 Customer Churn Analysis</h1>

    <section>
        <h2>📌 Project Overview</h2>
        <p>This project analyzes customer churn to identify key factors that lead to customer loss and provides actionable insights to improve retention.</p>
    </section>

    <section>
        <h2>🎯 Objectives & Goals</h2>
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
            <div>
                <h3>Analysis Focus</h3>
                <ul>
                    <li>Understand why customers leave</li>
                    <li>Identify churn drivers</li>
                </ul>
            </div>
            <div>
                <h3>Business Goal</h3>
                <ul>
                    <li>Reduce churn rate</li>
                    <li>Improve retention</li>
                    <li>Minimize revenue loss</li>
                </ul>
            </div>
        </div>
    </section>

    <section>
        <h2>📁 Dataset Description</h2>
        <p>The dataset contains <b>7,043 customers</b> and <b>21 features</b>, spanning demographics, services, and account details.</p>
        
        <h3>🔹 Features Overview</h3>
        <ul class="feature-list">
            <li>Gender & Seniority</li>
            <li>Tenure & Contract</li>
            <li>Payment Method</li>
            <li>Internet Service (Fiber/DSL)</li>
            <li>Tech Support</li>
            <li>Streaming Services</li>
            <li>Monthly/Total Charges</li>
        </ul>
    </section>

    <section>
        <h2>🛠️ Tech Stack</h2>
        <ul class="feature-list">
            <li>Python (Pandas/NumPy)</li>
            <li>SQL</li>
            <li>Power BI</li>
            <li>Excel</li>
        </ul>
    </section>

    <section>
        <h2>📊 Analysis Insights</h2>
        <h3>🔑 Key Findings</h3>
        <ul>
            <li>Overall churn rate is <b>26.58%</b>.</li>
            <li><b>Month-to-month contracts</b> are high risk (<b>42% churn</b>) compared to Two-year contracts (<b>3%</b>).</li>
            <li><b>Fiber optic users</b> show higher churn rates than DSL users.</li>
            <li>Higher monthly charges correlate strongly with customer loss.</li>
        </ul>

        <h3>📈 Key Performance Indicators (KPIs)</h3>
        <div class="table-container">
            <table>
                <thead>
                    <tr>
                        <th>KPI Metric</th>
                        <th>Value</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Overall Churn Rate</td>
                        <td>26.58%</td>
                    </tr>
                    <tr>
                        <td>Monthly Recurring Revenue (MRR)</td>
                        <td>$139,130.85</td>
                    </tr>
                    <tr>
                        <td>Avg. Tenure (Churned)</td>
                        <td>17.98 months</td>
                    </tr>
                    <tr>
                        <td>Avg. Customer Lifetime Value</td>
                        <td>$1,531.80</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    <section>
        <h2>💡 Strategic Recommendations</h2>
        <ul>
            <li><b>Incentivize Long-term Contracts:</b> Convert month-to-month users with discounts.</li>
            <li><b>Bundle Services:</b> Data shows customers with more services are stickier.</li>
            <li><b>Targeted Support:</b> Proactive outreach for Fiber Optic and Senior customers.</li>
        </ul>
    </section>

    <section class="footer-section">
        <h2>📬 Get In Touch</h2>
        <p>Let's discuss the data!</p>
        <p>
            <a href="mailto:godasaber6@gmail.com">Email</a> | 
            <a href="https://www.linkedin.com/in/goda-saber-426532287/" target="_blank">LinkedIn</a> | 
            <a href="https://github.com/GodaSaber" target="_blank">GitHub</a>
        </p>
    </section>
</div>

</body>
</html>
