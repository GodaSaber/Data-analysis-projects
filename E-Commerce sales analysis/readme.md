<h1>Global Sales Dataset Analysis</h1>

<p>
This project analyzes a global sales dataset containing <strong>2,000 records</strong> and
<strong>15 features</strong>, covering customer information, product performance, sales metrics,
profitability, regional distribution, shipping cost, and payment behavior.
The dataset is designed to support exploratory data analysis (EDA), business intelligence reporting,
and sales performance visualization.
</p>

<h2>Dataset Overview</h2>
<ul>
  <li><strong>Total Records:</strong> 2,000</li>
  <li><strong>Total Columns:</strong> 15</li>
  <li><strong>Missing Values:</strong> None</li>
  <li><strong>Memory Usage:</strong> 234.5 KB</li>
</ul>

<h2>Dataset Structure</h2>
<table>
  <thead>
    <tr>
      <th>Column Name</th>
      <th>Data Type</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Order_ID</td><td>object</td><td>Unique identifier for each order</td></tr>
    <tr><td>Order_Date</td><td>object</td><td>Date when the order was placed</td></tr>
    <tr><td>Customer_Name</td><td>object</td><td>Name of the customer</td></tr>
    <tr><td>Customer_Segment</td><td>object</td><td>Customer classification such as Consumer, Corporate, or Home Office</td></tr>
    <tr><td>Country</td><td>object</td><td>Country where the order was placed</td></tr>
    <tr><td>Region</td><td>object</td><td>Geographical region of the order</td></tr>
    <tr><td>Product_Category</td><td>object</td><td>Category of the purchased product</td></tr>
    <tr><td>Product_Name</td><td>object</td><td>Name of the product</td></tr>
    <tr><td>Quantity</td><td>int64</td><td>Number of units purchased</td></tr>
    <tr><td>Unit_Price</td><td>float64</td><td>Price per unit of the product</td></tr>
    <tr><td>Discount_Percent</td><td>int64</td><td>Discount percentage applied to the order</td></tr>
    <tr><td>Total_Sales</td><td>float64</td><td>Total revenue generated from the order</td></tr>
    <tr><td>Shipping_Cost</td><td>float64</td><td>Shipping cost associated with the order</td></tr>
    <tr><td>Profit</td><td>float64</td><td>Net profit earned from the order</td></tr>
    <tr><td>Payment_Method</td><td>object</td><td>Payment method used by the customer</td></tr>
  </tbody>
</table>

<h2>Key Business Insights</h2>

<h3>1. Product Category Performance</h3>
<ul>
  <li><strong>Technology</strong> is the best-performing category with <strong>567 orders</strong>.</li>
  <li><strong>Office Supplies</strong> follows with <strong>513 orders</strong>.</li>
  <li><strong>Furniture</strong> accounts for <strong>507 orders</strong>.</li>
  <li><strong>Clothing &amp; Accessories</strong> records <strong>413 orders</strong>.</li>
</ul>

<h3>2. Yearly Sales Trends by Product Category</h3>
<ul>
  <li>In <strong>2023</strong>, <strong>Technology</strong> led with <strong>188 orders</strong>.</li>
  <li>In <strong>2024</strong>, <strong>Technology</strong> remained the top category with <strong>185 orders</strong>.</li>
  <li>In <strong>2025</strong>, <strong>Technology</strong> increased further to <strong>194 orders</strong>, the highest yearly category count in the dataset.</li>
  <li><strong>Furniture</strong> also showed strong growth in <strong>2025</strong>, reaching <strong>190 orders</strong>.</li>
</ul>

<h3>3. Regional Performance</h3>
<ul>
  <li><strong>North America</strong> generated the highest order volume with <strong>578 orders</strong>.</li>
  <li><strong>Asia Pacific</strong> contributed <strong>520 orders</strong>.</li>
  <li><strong>Europe</strong> recorded <strong>503 orders</strong>.</li>
  <li><strong>Middle East &amp; Africa</strong> and <strong>South America</strong> had comparatively lower volumes with <strong>208</strong> and <strong>191</strong> orders, respectively.</li>
</ul>

<h3>4. Top Countries by Order Volume</h3>
<ul>
  <li><strong>Mexico</strong> ranked first with <strong>203 orders</strong>.</li>
  <li><strong>United States</strong> followed with <strong>196 orders</strong>.</li>
  <li><strong>Canada</strong> recorded <strong>179 orders</strong>.</li>
  <li>Within Asia Pacific, <strong>Japan</strong> had the strongest performance with <strong>124 orders</strong>.</li>
</ul>

<h3>5. Customer Segment Distribution</h3>
<ul>
  <li><strong>Consumer</strong> is the dominant segment with <strong>1,006 orders</strong>.</li>
  <li><strong>Corporate</strong> contributes <strong>623 orders</strong>.</li>
  <li><strong>Home Office</strong> represents <strong>371 orders</strong>.</li>
</ul>

<h3>6. Payment Method Trends</h3>
<ul>
  <li><strong>Credit Card</strong> is the most preferred payment method across all years.</li>
  <li><strong>PayPal</strong> is the second most-used payment channel and shows gradual growth over time.</li>
  <li><strong>Bank Transfer</strong> and <strong>Cash on Delivery</strong> are used less frequently but remain stable.</li>
</ul>

<h3>7. Weekly Order Trends</h3>
<ul>
  <li><strong>Tuesday</strong> recorded the highest number of orders with <strong>308</strong>.</li>
  <li><strong>Sunday</strong> and <strong>Wednesday</strong> also showed strong sales activity with <strong>303</strong> and <strong>293</strong> orders.</li>
  <li><strong>Monday</strong> had the lowest order volume with <strong>253 orders</strong>.</li>
</ul>

<h3>8. Most Profitable Products</h3>
<ul>
  <li><strong>Ergonomic Office Chair</strong> — <strong>359.63</strong></li>
  <li><strong>Corner L-Shaped Desk</strong> — <strong>350.33</strong></li>
  <li><strong>Standing Desk Converter</strong> — <strong>257.80</strong></li>
  <li><strong>Mesh Back Task Chair</strong> — <strong>217.29</strong></li>
  <li><strong>Wireless Bluetooth Headphones</strong> — <strong>189.48</strong></li>
</ul>

<h3>9. Low or Negative Profit Products</h3>
<ul>
  <li><strong>Sticky Notes Multicolor 6-Pack</strong> — <strong>1.59</strong></li>
  <li><strong>Highlighters Neon Pack 6</strong> — <strong>-0.01</strong></li>
  <li><strong>Paper Clips Box 500pc</strong> — <strong>-1.78</strong></li>
</ul>

<h3>10. Shipping Cost Analysis</h3>
<ul>
  <li>The lowest average shipping costs were observed in:
    <ul>
      <li><strong>United States</strong> — <strong>9.92</strong></li>
      <li><strong>Canada</strong> — <strong>9.99</strong></li>
      <li><strong>Mexico</strong> — <strong>10.22</strong></li>
    </ul>
  </li>
  <li>The highest average shipping costs were recorded in:
    <ul>
      <li><strong>UAE</strong> — <strong>16.44</strong></li>
      <li><strong>Nigeria</strong> — <strong>16.09</strong></li>
      <li><strong>South Africa</strong> — <strong>16.01</strong></li>
      <li><strong>Argentina</strong> — <strong>16.00</strong></li>
    </ul>
  </li>
</ul>

<h2>Summary</h2>
<p>
The analysis indicates that <strong>Technology</strong> is the leading product category,
<strong>North America</strong> is the strongest-performing region, and <strong>Credit Card</strong>
is the most commonly used payment method. High-profit items are concentrated in
<strong>furniture</strong> and <strong>technology-related products</strong>, while several
low-cost office supply products generate minimal or negative profit. Additionally,
shipping costs are lowest in North America and highest in selected countries across
the Middle East, Africa, and South America.
</p>

<h2>Use Cases</h2>
<ul>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Sales performance dashboards</li>
  <li>Regional and country-level market analysis</li>
  <li>Customer segmentation analysis</li>
  <li>Profitability and pricing strategy evaluation</li>
  <li>Payment method and shipping cost optimization</li>
</ul>
