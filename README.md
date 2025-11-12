# E-commerice-Analysis-Dashboard
# 📊 E-Commerce Data Analysis Dashboard (Python/Jupyter)

## Project Overview

This project presents a comprehensive data analysis and visualization dashboard for an E-commerce platform. It leverages Python's data science stack to clean, process, and analyze transactional data, product information, customer demographics, and user ratings. The primary goal is to derive actionable insights into sales performance, customer behavior, and product popularity, which can inform strategic business decisions.

The analysis is performed within a **Jupyter Notebook** (`E-Commerce Analysis Dashboard.ipynb`), providing a step-by-step documentation of the data pipeline and visualization process.

## Key Features & Analysis Performed

* **Sales Performance Analysis:** Tracking overall sales trends, revenue over time, and identifying peak sales periods.
* **Product Analysis:** Identifying best-selling and worst-selling products, analyzing sales distribution across different product categories.
* **Customer Segmentation (RFM):** Applying the **Recency, Frequency, Monetary (RFM)** model to segment customers into groups (e.g., 'Champions', 'Loyal Customers', 'At Risk') for targeted marketing campaigns.
* **Rating and Review Analysis:** Calculating average ratings per product and identifying highly-rated items.
* **Data Merging and Cleaning:** Demonstrates proficiency in joining data from multiple relational sources and handling data types.

## Data Sources

The dashboard utilizes five synthesized or anonymized CSV files:

| File Name | Description |
| :--- | :--- |
| `orders.csv` | Transactional data, including `order_id`, `customer_id`, `product_id`, `order_date`, and `quantity`. |
| `products.csv` | Product master data, including `product_id`, `product_name`, `price`, and `category`. |
| `customers.csv` | Customer demographics, including `customer_id` and `name`. |
| `ratings.csv` | User-submitted ratings for products, including `customer_id`, `product_id`, and `rating`. |
