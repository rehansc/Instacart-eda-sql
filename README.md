
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

- **Databricks (Community Edition)** for Spark SQL and notebooks
- **PySpark SQL** for querying large-scale datasets
- **Pandas** for data wrangling
- **Matplotlib & Seaborn** for visualizations

> 🧠 This analysis was conducted entirely in **Databricks Community Edition** using Spark SQL, PySpark, and Python visualizations.

---

## 📁 View the Code & Outputs

- [📄 View full notebook source (`.ipynb`)](https://github.com/rehansc/Instacart-eda-sql/blob/main/instacart_eda_sql.ipynb)


---

## 📊 Visualizations

## 📊 Visual Results

### 1. **Top 10 Most Ordered Products**
Shows the most frequently purchased products across all orders.
![Top Products](images/top_products.png)

### 2. **Top 10 Most Reordered Aisles**
Highlights aisles with highest reorder rates — staple categories.
![Reordered Aisles](images/reordered_aisles.png)

### 3. **Top 10 Users with Highest Average Basket Size**
Identifies users who place large orders, indicating high-value behavior.
![Top Users](images/top_users.png)

### 4. **Basket Size Distribution**
A histogram showing how many items are typically ordered.
![Basket Size Distribution](images/basket_hist.png)

### 5. **Order Count by Day of Week and Hour of Day**
Heatmap showing time-of-day and day-of-week order trends.
![Orders by Day/Hour](images/dow_hour_heatmap.png)

---

## 💡 Key Business Insights

- **Produce & dairy dominate reorders** → Opportunity for upsell/retargeting.
- **High-value users place large baskets** → Focus for loyalty/retention.
- **Peak shopping: weekends, late mornings** → Ideal ad & ops timing.
- **Most baskets are 5–15 items** → Promotions can nudge to higher order values.

---

## 📁 Suggested Repository Structure

```
instacart-eda-sql/
├── instacart_eda_sql.ipynb
├── images/
│   ├── top_products.png
│   ├── reordered_aisles.png
│   ├── top_users.png
│   ├── basket_hist.png
│   └── dow_hour_heatmap.png
└── README.md

```
---

## ✅ Next Steps

- Add predictive modeling (e.g., reorder prediction)
- Build dashboards (Power BI, Tableau, or Streamlit)
- Expand to personalized recommendations

---

## ▶️ Run It Yourself
1. Sign up for [Databricks Community Edition](https://community.cloud.databricks.com/).
2. Upload the Instacart dataset CSVs to `dbfs:/FileStore/tables/instacart/`.
3. Import `instacart_eda_sql.ipynb` into Databricks.
4. Run the notebook cells in order.

---

**Skills Demonstrated**:
- Data querying with Spark SQL
- Data cleaning & transformation (PySpark, Pandas)
- Visualization (Matplotlib, Seaborn)
- Business insight generation

---

## 🔗 Author

**Rehan Chaudhry**  
[GitHub Portfolio](https://github.com/rehansc)  
[LinkedIn](https://www.linkedin.com/in/rehanchaudhry/)


---
