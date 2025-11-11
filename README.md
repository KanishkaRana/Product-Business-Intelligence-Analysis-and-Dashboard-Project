# 📊 Sony India: Business and Product Intelligence Dashboard

This project is a comprehensive Business and Product Intelligence solution for Sony India, designed to provide data-driven insights into sales performance, customer behavior, and product profitability. The solution utilizes data cleaning and formatting in **Microsoft Excel** and professional visualization in **Microsoft Power BI** to support strategic decision-making.



---

## 🎯 Project Goal

The primary objective of this project was to transform raw transactional data (Sales, Products, Customers, Subscriptions) into actionable intelligence. The dashboard focuses on answering key business questions related to:
1.  **Sales Performance:** Tracking revenue trends and geographic contribution.
2.  **Product Health:** Analyzing profit margins by category and identifying high-value products.
3.  **Customer Lifecycle:** Monitoring order status and acquisition channels.

---

## 🛠️ Technologies Used

| Tool | Purpose |
| :--- | :--- |
| **Microsoft Power BI** | Data modeling, ETL (Power Query), visualization, and creating the final interactive dashboard. |
| **Microsoft Excel** | Initial data cleaning, formatting, and preparation of raw CSV files (e.g., handling missing values, standardizing formats). |
| **DAX (Data Analysis Expressions)** | Creating calculated measures and columns (e.g., Total Revenue, Profit Margin % calculation, etc.). |

---

## 📂 Data Sources

The analysis is based on four interlinked datasets, sourced from an imagined Sony India transactional database.

| File Name | Description | Key Fields |
| :--- | :--- | :--- |
| `customers.csv` | Customer demographics and acquisition details. | `customer_id`, `state`, `marketing_channel` |
| `products.csv` | Product master data, pricing, and profitability metrics. | `product_id`, `product_name`, `category`, `profit_margin` |
| `orders.csv` | Transactional data for product sales. | `order_id`, `customer_id`, `product_id`, `total_amount`, `order_status` |
| `subscriptions.csv` | Status and renewal data for recurring subscription services. | `subscription_id`, `status`, `renewal_count` |

---

## 📈 Key Dashboard Components & Metrics

The dashboard provides a holistic view across several dimensions:

* **Key Performance Indicator (KPI) Cards:**
    * **Total Revenue:** `$48M` (Sum of `total_amount` over three years).
    * **Order Status Count:** Breakdown of Active, Cancelled, and Expired orders.
* **Time Series Analysis:** Revenue trend (`Sum of total_amount` by `MonthNumber` and `Year`).
* **Geographic Analysis:** Revenue contribution by `State`.
* **Marketing & Segmentation:** Revenue distribution by `gender` and `marketing_channel`.
* **Product Intelligence:** Analysis of product categories based on `profit_margin`.
* **High-Value Insights:** Specific metrics for critical products like **PS5 DualSense Controller** and **Bravia 65-inch 4K TV**.

---

## ✨ Visible Project Insights (Analysis Snapshot)

Based on the dashboard visuals, the following key insights were drawn for Sony India:

1.  **High Revenue Concentration in Key States:** The **Maharashtra** region appears to be the primary revenue driver, contributing the largest share of the $48M Total Revenue. This suggests marketing or sales focus should be maintained or scaled in this region.
2.  **Marketing Channel Efficiency:** The **Email** channel generates the highest total revenue among all marketing channels, making it the most successful avenue for customer acquisition or retention efforts.
3.  **Customer Lifecycle Status:** The vast majority of customer orders are in the **Completed** status, which is a strong indicator of successful order fulfillment and customer satisfaction.
4.  **Profitability Analysis:** The **Camera** category has the highest average profit margin compared to other product categories (Subscription, TV, Gaming, Headphones), making it a key strategic area for profit growth.
5.  **High-Value Product Performance:** Specific insights are highlighted for top products: the **PS5 DualSense Controller** shows a high profit margin (29%), while the **Bravia 65-inch 4K TV** shows a relatively lower profit margin (12%), suggesting a potential focus on volume over margin for the high-end TV segment.

---

## 🚀 Future Scope

* Implement a **What-If Analysis** to model the impact of changing product prices or marketing spend.
* Integrate **Customer Lifetime Value (CLV)** analysis for deeper customer segmentation.
* Develop a separate dashboard focusing on **Supply Chain and Inventory**.
<img width="698" height="392" alt="product_bi(dashboardSS)" src="https://github.com/user-attachments/assets/a7fa89b0-c093-4d73-8f8f-8f54be0a65ce" />
