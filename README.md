# 🛒 E-Commerce Analytics Dashboard

![ecommerce\_banner](screenshots/sales_dashboard.png)

# 📦 Welcome to the **E-Commerce Analytics Project**!

This repository features an end-to-end data analysis project on e-commerce sales, customer behavior, seller performance, and product category trends. It leverages advanced SQL for insight extraction and Power BI for intuitive data storytelling.

---

## 📌 Project Overview

This project analyzes transactional data from an e-commerce platform to uncover trends and business insights across:

* Total revenue and monthly sales dynamics
* Customer type analysis (repeat vs. one-time)
* Seller growth and category performance
* Product popularity and seasonality
* Influence of ratings and delivery delays on sales

---

## 🛍️ Dataset Information

The database comprises 7 interlinked tables:

* **Customers**
* **Orders**
* **Payments**
* **Products**
* **Order Items**
* **Reviews**
* **Sellers**

It spans from **Sept 2022 to Oct 2025**, covering sales, feedback, and transaction flows.

---

## 📚 Source

Data derived from a public e-commerce transactional dataset similar to the **Olist Dataset** available on **Kaggle**. It includes anonymized real-world order-level data.

---

## 📊 Key Highlights

### 💰 **1. Revenue Trends**

* Total Revenue: ₹16.01M+
* Peak: April 2018; Drop in Oct 2018

### 👤 **2. Customer Behavior**

* 84.5% sales by One-Time Buyers
* Repeat buyers contribute 15.4% revenue

### 📦 **3. Best-Selling Products**

* Top Quantity: Bed, Table & Bath
* High Value: Beauty & Health, Watches & Gifts
* Seasonal spikes in Gifts, Fitness

### 🛍️ **4. Seller Growth**

* Grew from 219 (Jan 2017) to 1,261 (Aug 2018)

### ⭐ **5. Review Impact**

* 5-star rated products dominate sales
* Delay in delivery linked to poor ratings

---

## 📂 Visualizations

### 📊 Power BI Dashboard Preview

<p align="center">
  <img src="screenshots/sales_dashboard_page1.jpg" alt="Power BI Dashboard Preview" width="800"/>
</p>

> 📈 *This dashboard page highlights monthly revenue, order trends, average order value, and customer behavior split.*

Other dashboards include:

* Revenue & Orders over Time
* Repeat vs One-Time Customer Split
* Product Category Performance
* Review Score Impact on Sales
* Seller Growth Trends

---

## 🧰 Technologies Used

* **SQL Server**: Querying, data joins, and metrics extraction
* **Power BI**: Dashboards and trend visualization
* **CSV/Excel**: Data export and transformation
* **GitHub**: Project collaboration and versioning

---

## 🛠️ Installation and Usage

### For SQL Analysis:

1. Load `.sql` file into **SQL Server Management Studio**.
2. Run each query to extract relevant insights.
3. Export outputs as `.csv` for Power BI if needed.

### For Power BI Dashboard:

1. Open `Ecommerce_Analytics.pbix` in Power BI Desktop.
2. Connect to `.csv` or live SQL data.
3. Interact with the dashboard using filters and visuals.

---

## 📁 Project Structure

```bash
ecommerce-sales-insights-sql-powerbi/
│
├── data/
│   ├── raw_data.csv                  # Original exports
│   └── cleaned_data.csv              # Power BI-ready format
│
├── sql_queries/
│   └── ecommerce_analysis.sql        # Core SQL scripts
│
├── visualizations/
│   └── Ecommerce_Analytics.pbix      # Power BI report
│
├── screenshots/
│   └── sales_dashboard.png           # Dashboard image preview
│
├── README.md                         # Project documentation
```

---

## 🔮 Future Enhancements

* Integrate ML models to predict high-value customers
* RFM segmentation for targeted marketing
* Real-time dashboard with Power BI service or Python

