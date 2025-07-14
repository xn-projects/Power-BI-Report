# 📊 Power BI Analytical Report on the Olist Project

## Project Overview

This project presents an analysis of data from the Brazilian company **Olist** — a marketplace that helps small and medium-sized stores sell their products through an online platform. The dataset contains data on orders, products, sellers, customers, payments, logistics, and customer reviews.

**Project Goal:**  
To visualize key business metrics, identify patterns in sales and product delivery, and assess the level of customer satisfaction.

The interactive report was developed in **Power BI** and consists of six pages:
- Summary Report
- Sales
- Payments
- Logistics
- Reviews
- Products

---

## 📌 Report Structure

### 1️⃣ Summary Report

The Summary Report is the starting point of the report. It includes four blocks:
- **Key Sales Metrics:** revenue, average invoice, number of deals, conversion rate (stacked area chart + year-over-year comparison).
- **Payments:** active customers and sellers, outstanding balance for delivered orders, pie chart of payment methods.
- **Customer Ratings:** distribution of ratings by product categories. Empty values are grouped as “Other.” Conditional formatting: above average — green, below — red.
- **Delivery:** on-time delivery rate, canceled orders, order volume and weight, order cycle time. The table shows the top 5 categories by on-time delivery rate.

📎 **Navigation:** buttons on the left side, the active page is highlighted by color, tooltips appear on hover.

---

### 2️⃣ Sales Page

- Number of potential sales by month with trends and year-over-year comparison.
- Total value of orders in progress.
- Two pie charts: revenue by product name length and number of sales by product description length.
- Revenue chart by year.
- Sales funnel: potential orders → approved → sent for delivery → delivered.
- Table of revenue distribution by categories.

---

### 3️⃣ Payments Page

- Total payment amount, amount for delivered orders, unpaid orders, and outstanding balance.
- Percentage of installments and average payment size.
- Line chart showing payment trends by month.
- Pie chart of payment counts.
- Decomposition tree of revenue by payment method and category.

💡 A parameter based on DAX is used to switch between order statuses (*confirmed*, *canceled*, *in progress*).

---

### 4️⃣ Logistics Page

- Average order processing time, delivery time, and full order cycle time.
- Cost per order unit, per kilogram, and per delivery.
- Share of on-time deliveries, number of deliveries, average weight and volume.
- Area chart: difference between expected and actual delivery dates.
- Donut chart: number of on-time deliveries by weight category (*heavy*, *medium*, *light*).
- Clustered column chart: average processing and delivery time by category.

---

### 5️⃣ Reviews Page

- Number of reviews, average rating, percentage of pre-order reviews.
- Metric of positive and negative reviews.
- Table with buyer’s location and rating.
- Pie chart of rating characteristics (*Very Satisfied*, *Satisfied*, *Neutral*, etc.).
- Chart: average days to respond to positive and negative reviews.
- Line chart: average days until a review is left.
- Distribution of positive and negative reviews by month.

---

### 6️⃣ Products Page

- Map of seller distribution by potential sales.
- Line chart of sales and revenue trends.
- Comparative table of metrics with growth/decline icons.
- Filtering by category or overall view.

---

## 🔗 Data Model

The model is built on relationships between fact tables (*orders, payments, delivery*) and dimension tables (*customers, sellers, products, categories*). Relationships via key fields provide flexibility for visualization and drill-down analysis.

---

## ✅ Conclusion

The interactive Power BI report demonstrates:
- Sales and payment dynamics
- Identification of logistical bottlenecks
- Analysis of reviews and customer satisfaction

Using this report helps make informed decisions and build a robust business development strategy.

---

## 🛠️ Technologies
- **Power BI**
- **DAX**
- Interactive charts and maps
- Intuitive navigation and filtering

---

The interactive Power BI dashboard file is available for download here:  
[🔗 Download Olist_Sales_Report.pbix on Google Drive](https://drive.google.com/file/d/1jUmrATPZkhFti1vk2C4QRpEhl6lkyZgh/view?usp=sharing)

Please note: Due to GitHub’s file size limitations, the .pbix file is hosted externally on Google Drive.
