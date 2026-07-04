# 📊 E-Commerce Order Analytics Dashboard

An end-to-end data analytics project that transforms raw e-commerce order data into clear, actionable business insights using **Python**, **SQL**, and **Power BI**.

![Dashboard Preview](dashboard_preview.png)

---

## 📌 Project Overview

This project analyzes e-commerce order data to uncover trends in sales, customer behavior, payment preferences, and referral channel performance. It covers the complete analytics workflow — from raw data cleaning to an interactive Power BI dashboard — reflecting how real-world business data is processed and turned into decision-ready insights.

**Key metrics tracked:**
- 🛒 886 Total Orders
- 📦 2,579 Units Sold
- 💰 ₹938.81K Total Revenue

---

## 🔍 What the Dashboard Covers

- 🚦 **Order Status Tracking** — Delivered, Shipped, Pending, Cancelled & Returned
- 📢 **Referral Source Performance** — Instagram, Google, Email, Facebook & Referral
- 💳 **Payment Method Analysis** — Cash, Credit/Debit Card, Online & Gift Card
- 🖥️ **Product-Wise Sales Breakdown** — Laptop, Phone, Monitor, Chair, Desk, Printer & Tablet
- 📅 **Monthly Trend Analysis** — spotting seasonal patterns in revenue
- 🎛️ **Interactive Filters & Drill-Through** — for deeper, on-demand exploration

---

## 🛠️ Tech Stack

| Stage | Tools Used |
|---|---|
| Data Cleaning | Python (Pandas) |
| Exploratory Data Analysis | Python (Pandas, Matplotlib, Seaborn, Statsmodels) |
| Data Querying | SQL (SQLite) |
| Dashboard & Visualization | Power BI |

---

## 📂 Project Structure

```
Internship_Project/
│
├── raw/
│   └── Dataset.xlsx              # Original, unprocessed order data
│
├── processed/
│   └── cleaned_dataset.xlsx      # Cleaned dataset ready for analysis
│
├── script/
│   ├── Project1.ipynb            # Data cleaning & preprocessing
│   ├── Project2.ipynb            # Exploratory data analysis (EDA)
│   ├── Project3.ipynb            # SQL-based querying & analysis
│   └── ecommerce.db              # SQLite database for SQL analysis
│
└── Project4Dashboard.pbix        # Power BI dashboard file
```

---

## 🧹 Workflow

**1. Data Cleaning** (`Project1.ipynb`)
Handled missing values, removed duplicate records, standardized data types, and prepared a clean dataset for analysis.

**2. Exploratory Data Analysis** (`Project2.ipynb`)
Analyzed distributions, detected outliers, examined correlations, and studied sales trends over time, including seasonal decomposition.

**3. SQL Analysis** (`Project3.ipynb`)
Loaded the cleaned data into a SQLite database and used SQL queries to extract insights on revenue, order status, product performance, and payment behavior.

**4. Dashboard Design** (`Project4Dashboard.pbix`)
Consolidated all insights into an interactive Power BI dashboard with dynamic filters, KPI cards, and drill-through capability for a complete, at-a-glance view of business performance.

---

## 🚀 Key Insights

- Products are fairly evenly distributed in sales volume, with Monitor, Laptop, and Phone among the top performers.
- Referral traffic from Instagram and Google significantly outperforms other channels in driving orders.
- Digital payment methods (Online, Credit/Debit Card) are the most preferred among customers.
- Order status is well distributed across the fulfillment pipeline, with a healthy delivery rate relative to cancellations and returns.

---

## 📎 How to Use

1. Clone this repository
2. Open `Project4Dashboard.pbix` in **Power BI Desktop** to explore the interactive dashboard
3. Explore the Jupyter notebooks in `script/` to review the data cleaning, EDA, and SQL analysis workflow

---

## 🙋 About This Project

This project was independently designed and developed to strengthen practical skills in data cleaning, exploratory analysis, SQL querying, and dashboard design — using a real-world style e-commerce dataset.

---

## 📬 Connect

Feel free to explore the project, raise issues, or connect with me for feedback and collaboration opportunities in data analytics! 💬
