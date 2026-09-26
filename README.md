# Olist E-Commerce Analytics

## 📌 Project Overview

This project analyzes the Brazilian Olist e-commerce dataset to understand sales performance, customer behavior, product performance, seller performance, payment methods, delivery performance, and geographic sales patterns.

The project uses Python, Pandas, NumPy, Plotly, and Matplotlib to perform data cleaning, exploratory data analysis, business analysis, and interactive dashboard development.

---

## 🎯 Project Objectives

* Analyze overall e-commerce sales performance
* Identify top-performing product categories
* Understand customer purchasing and retention behavior
* Analyze seller performance
* Evaluate delivery performance and its impact on customer satisfaction
* Understand payment method preferences
* Identify high-performing customer states
* Analyze shipping and freight costs
* Generate actionable business recommendations

---

## 📊 Dataset

The project uses the **Brazilian Olist E-Commerce Dataset**, containing information about:

* Customers
* Orders
* Order items
* Products
* Sellers
* Payments
* Reviews
* Product categories
* Geolocation

The dataset contains approximately 99,000 orders and more than 112,000 order items.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Plotly**
* **Jupyter Notebook**
* **CSV**
* **Exploratory Data Analysis**
* **Data Visualization**
* **Business Analytics**

---

## 🔍 Data Cleaning

The following data preparation steps were performed:

* Checked dataset dimensions and data types
* Identified missing values
* Converted date columns to datetime format
* Handled missing product information
* Filled missing review comments with appropriate placeholders
* Used median imputation for missing numerical product attributes
* Removed exact duplicate geolocation records
* Checked duplicate records across all major datasets
* Created derived variables for delivery analysis

Delivery-related missing dates were retained where appropriate because they can contain meaningful information about order status.

---

## 📈 Key KPIs

| KPI                   |     Value |
| --------------------- | --------: |
| Total Orders          |    99,441 |
| Total Customers       |    96,096 |
| Total Products        |    32,951 |
| Total Sellers         |     3,095 |
| Total Items Sold      |   112,650 |
| Product Revenue       |   ₹13.59M |
| Total Freight         |    ₹2.25M |
| Average Order Value   |   ₹160.58 |
| Average Review Score  |  4.09 / 5 |
| Average Delivery Time | 12.1 days |

---

## 💡 Key Business Insights

### 1. Delivery Performance

Delivery performance has a strong relationship with customer satisfaction.

* Early deliveries → **4.29/5 average rating**
* Late deliveries → **2.11/5 average rating**

This indicates that improving delivery reliability can have a significant impact on customer satisfaction.

### 2. Customer Retention

The majority of customers are one-time purchasers.

* One-time customers → **96.88%**
* Repeat customers → **3.12%**

This suggests a major opportunity to improve customer retention through loyalty programs, personalized offers, and targeted remarketing.

### 3. Payment Methods

Credit cards are the dominant payment method, accounting for the majority of payment transactions and payment value.

This indicates that maintaining a smooth and secure card-payment experience is important for the business.

### 4. Geographic Sales

São Paulo (SP) is the strongest customer market by a significant margin, followed by Rio de Janeiro (RJ) and Minas Gerais (MG).

This suggests that these regions are particularly important for sales, marketing, and logistics planning.

### 5. Product Categories

Several categories generate substantial revenue but have average ratings below 4.0.

These categories should be monitored because improving product quality, seller quality, product descriptions, or fulfillment could improve customer satisfaction.

### 6. Seller Performance

Seller performance varies significantly in terms of revenue, sales volume, and customer ratings.

Low-rated sellers with meaningful sales volume should be investigated to identify issues related to product quality, fulfillment, or customer service.

---

## 📊 Dashboard

The project includes two interactive Plotly dashboards:

### Executive Dashboard

Provides an overview of:

* Revenue trends
* Order status
* Top product categories
* Customer loyalty
* Delivery and customer ratings
* Payment methods

### Sellers & Logistics Dashboard

Provides analysis of:

* Top sellers
* Top customer states
* Shipping freight costs
* Low-rated sellers

---

## 📁 Project Structure

```text
Olist_Ecommerce_Analytics/
│
├── data/
│   └── raw/
│       ├── olist_customers_dataset.csv
│       ├── olist_orders_dataset.csv
│       ├── olist_order_items_dataset.csv
│       ├── olist_order_payments_dataset.csv
│       ├── olist_order_reviews_dataset.csv
│       ├── olist_products_dataset.csv
│       ├── olist_sellers_dataset.csv
│       ├── product_category_name_translation.csv
│       └── olist_geolocation_dataset.csv
│
├── notebooks/
│   └── Olist_Ecommerce_Analysis.ipynb
│
├── dashboard/
│   ├── Olist_Executive_Dashboard.html
│   └── Olist_Sellers_Logistics_Dashboard.html
│
├── outputs/
│   ├── olist_dashboard_kpis.csv
│   ├── olist_dashboard_monthly.csv
│   ├── olist_dashboard_categories.csv
│   ├── olist_dashboard_payments.csv
│   ├── olist_dashboard_customer_loyalty.csv
│   ├── olist_dashboard_delivery.csv
│   ├── olist_dashboard_states.csv
│   ├── olist_dashboard_sellers.csv
│   └── olist_final_business_insights.csv
│
└── README.md
```

---

## 🚀 Business Recommendations

Based on the analysis, the following actions are recommended:

1. **Improve delivery reliability** to reduce late deliveries and improve customer satisfaction.
2. **Increase customer retention** through loyalty programs and personalized promotions.
3. **Monitor low-rated sellers** with sufficient sales volume and investigate recurring customer complaints.
4. **Focus marketing efforts on high-performing regions**, particularly major revenue-generating states.
5. **Optimize logistics and freight costs** by analyzing regional seller and customer locations.
6. **Improve underperforming high-revenue categories** by addressing product quality and fulfillment issues.
7. **Continue supporting popular payment methods**, particularly credit-card payments.

---

## 📌 Project Outcome

This project demonstrates the ability to transform raw e-commerce data into meaningful business insights using Python and interactive data visualization.

The analysis follows the complete analytics workflow:

**Data Collection → Data Cleaning → EDA → Business Analysis → Visualization → Insights → Recommendations → Dashboard**

---

## 👩‍💻 Author

**Shrushti Shelgave**

BSc Computer Science
Aspiring Data Analyst

