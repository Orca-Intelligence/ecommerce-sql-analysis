# 🛒 E-Commerce SQL Analytics Project

This project uses the [Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) from Kaggle to simulate real-world business analysis using SQL. The goal is to explore customer behavior, order processing, product sales, and delivery performance using PostgreSQL.

---

## 📦 Dataset Description

The dataset contains detailed information about orders made at a Brazilian e-commerce platform between 2016 and 2018. It includes:

- olist_customers_dataset
- olist_geolocation_dataset
- olist_order_items_dataset
- olist_order_payments_dataset
- olist_order_reviews_dataset
- olist_orders_dataset
- olist_products_dataset
- olist_sellers_dataset
- product_category_name_translation

📌 **Source**: [Kaggle - Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 🧰 Tools & Technologies

- **PostgreSQL** (via pgAdmin)
- **SQL** (Joins, Aggregates, CTEs, Subqueries, Window Functions)
- **Git & GitHub**
- **Kaggle CSV files**

---

## 🎯 Project Objectives

- Design normalized relational schema from real-world data
- Perform advanced SQL operations for business insights
- Practice interview-level SQL problems (joins, subqueries, CTEs, window functions)
- Prepare a portfolio-ready, recruiter-visible SQL project

---

## 🗂️ Project Structure

```bash
ecommerce-sql-analysis/
├── README.md                  # Project documentation
├── sql/
│   ├── 01_create_tables.sql   # Schema creation script
│   ├── 02_joins.sql           # Practice joins
│   ├── 03_groupby.sql         # Aggregations
│   ├── 04_window.sql          # Window functions
│   ├── 05_subqueries.sql      # Subqueries
│   ├── 06_ctes.sql            # CTEs and recursive CTEs
│   └── 07_final_queries.sql   # Final business questions
├── insights.md                # Summary of analytical insights
├── er_diagram.png             # Optional - Schema diagram
└── data/                      # (optional) Sample CSVs or Kaggle link
