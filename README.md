# 🍕 Pizza Sales Data Analysis (SQL)

## 📌 Project Overview
**Author:** Prachi Aswani
**Tool Used:** SQL (MySQL)

This project analyzes transactional data from a pizza outlet to key performance indicators (KPIs) regarding **sales trends, inventory management, and customer behavior**. The goal was to transition from raw data to actionable insights.

## 📂 Key Business Metrics (KPIs)
Based on the analysis of **21,350 orders**, the following insights were derived:

- **💰 Total Revenue:** $817,860.05
- **📦 Total Orders:** 21,350
- **🍕 Best Selling Pizza (Revenue):** The Thai Chicken Pizza
- **💸 Highest Priced Item:** The Greek Pizza ($35.95)
- **🕐 Busiest Time:** 18:00 (6 PM) with 2,399 orders

## 🛠️ Technical Skills Demonstrated
This project showcases advanced SQL techniques, including:
- **Aggregations:** `SUM`, `COUNT`, `AVG` to calculate KPIs.
- **Joins:** Combining 4 tables (`orders`, `order_details`, `pizzas`, `pizza_types`) for comprehensive analysis.
- **Window Functions:** Used `RANK()` to find top products per category and `SUM() OVER()` for cumulative revenue.
- **Subqueries & CTEs:** Nested queries for complex calculations like percentage contribution.

## 📊 Analysis & Insights
### 1. Sales Trends
- **Daily Average:** The store sells an average of **138 pizzas per day**.
- **Peak Hours:** Sales peak during lunch (12 PM - 1 PM) and dinner (5 PM - 8 PM), with the maximum orders at **6 PM**.

### 2. Product Performance
- **Most Common Size:** Large (L) pizzas account for the majority of sales (18,526 orders).
- **Top Category:** The **"Classic"** category contributes the most to total revenue (26.91%), followed closely by Supreme (25.46%).

### 3. Advanced Revenue Analysis
- Calculated **Cumulative Revenue** over time to track growth stability.
- Used **Ranking** to identify the top 3 revenue-generating pizzas within *each* specific category (Chicken, Classic, Supreme, Veggie).

## 🚀 How to Run This Project
1. Download the `Pizza_Analysis.sql` file from this repository.
2. Import the dataset into your MySQL Workbench.
3. Run the queries to verify the insights.

---
*Analysis by Prachi Aswani*
