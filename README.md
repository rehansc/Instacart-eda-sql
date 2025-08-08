# Instacart-eda-sql

# 🛒 Instacart Market Basket Analysis (SQL + Python)

This project explores Instacart's real-world grocery ordering data using **Databricks SQL** and **Python visualizations**. It simulates how a Data Scientist at Instacart might analyze shopping behaviors to generate actionable business insights.

---

## 📦 Dataset

The data comes from the [Instacart Market Basket 2017 dataset](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data) and includes:

- `orders.csv`: metadata for each order placed by users
- `order_products__prior.csv`: prior order details (product-level)
- `products.csv`, `aisles.csv`, `departments.csv`: metadata for each product

---

## 🛠 Tools Used

- **Databricks (Community Edition)** for Spark SQL and notebook environment
- **PySpark SQL** for querying large-scale datasets
- **Pandas** for in-memory data manipulation
- **Matplotlib & Seaborn** for data visualization

---

## 📊 Visualizations

### 1. **Top 10 Most Ordered Products**
Shows the most frequently purchased products across all orders.

### 2. **Top 10 Most Reordered Aisles**
Highlights which aisles (e.g., produce, dairy) have the highest reorder rates — insight into staple categories.

### 3. **Top 10 Users with Highest Average Basket Size**
Identifies users who typically place large orders, which could indicate high lifetime value customers.

### 4. **Basket Size Distribution**
A histogram showing how many items are typically ordered — most baskets have 5–15 items.

### 5. **Order Count by Day of Week and Hour of Day**
A heatmap to visualize shopping behavior patterns, showing peaks on weekends and afternoons.

---

## 💡 Business Insights

- **Produce & Dairy dominate reorders**: Suggests strong repeat behavior in staple items, offering opportunities for retention and upsell targeting.
- **Small group of users place large baskets**: These users may be ideal for loyalty programs or bulk promotions.
- **Peak shopping occurs late mornings to early afternoons on weekends**: Perfect timing for ad targeting, promotions, or staffing adjustments.
- **Most baskets are medium-sized**: Encourages designing promotions for customers adding “just a few more items” to optimize average order value.

---

## 📁 Project Structure

```
📦 instacart-eda
├── instacart_week1_notebook.py      # Databricks notebook exported as .py
├── README.md                        # This file
└── /images                          # Screenshots of visualizations (optional)
```

---

## ✅ Next Steps

- Add predictive modeling (e.g., reorder prediction, basket prediction)
- Connect to Power BI or Tableau for stakeholder dashboards
- Create a Streamlit app or Databricks dashboard for interactivity

---

## 🔗 Author
**Rehan Chaudhry**  
[GitHub Portfolio](https://github.com/rehansc)  
[LinkedIn](https://www.linkedin.com/in/RehanChaudhry)

---
