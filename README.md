# 📊 Power BI Analytics Dashboard

> A comprehensive data analysis dashboard created using Microsoft Power BI to extract meaningful insights.

### 🛠️ Key Insights & Features
* **Data Source:** Cleaned and transformed raw data.
* **Key Metrics:** Tracked Sales, Revenue, and User growth using KPIs.
* **Interactive Filters:** Added Slicers for deep-dive regional analysis.

# 🛍️ Madhav Ecommerce Store Sales Dashboard

An interactive and data-driven **Power BI Dashboard** built from raw ecommerce datasets. This project demonstrates the end-to-end Business Intelligence (BI) process: taking raw, uncleaned data from a local PC, transforming it, establishing data models, and creating actionable visual insights to track sales and profit performance.

---

## 📊 Project Overview & Objective

The objective of this project is to analyze the sales performance of "Madhav Store", an ecommerce platform operating in India. By transforming raw transactional data into visual insights, this dashboard helps the store owner understand customer behavior, target high-performing regions, optimize product inventory, and make data-backed strategic decisions.

---

## ⚡ Key Insights & Business Value

* **Top Performing Category:** The `Clothing` category generated the highest volume of orders and units sold.
* **Geographical Leaders:** `Madhya Pradesh` and `Maharashtra` emerged as the top-performing states, contributing the highest sales and profit margins.
* **Customer Preferences:** `Cash on Delivery (COD)` remains the most preferred payment method, followed by UPI.
* **Peak Sales Season:** A massive spike in revenue and profit was observed during the holiday season in Quarter 4 (Q4).
* **Target Audience:** Identified the top 5 premium customers who contribute significantly to the store's high-value orders.

---

## 🛠️ Data Pipeline & Technical Architecture

Since this project started with **raw data** stored locally, the following end-to-end BI workflow was implemented:

1. **Data Extraction:** Imported raw `Orders` and `Details` CSV datasets into Power BI.
2. **Data Cleaning & Transformation (Power Query):** 
   * Handled missing values, null spaces, and duplicate records.
   * Fixed and standardized data types (e.g., converting dates, currency formats).
   * Promoted headers and split columns where necessary for cleaner analysis.
3. **Data Modeling:** Designed a relational schema to connect the `Orders` and `Details` tables effectively.
4. **DAX Calculations:** Written Data Analysis Expressions (DAX) to create dynamic metrics such as *Total Sales*, *Total Profit*, *Quantity Sold*, and *Average Order Value (AOV)*.
5. **Data Visualization:** Built a modern, clean, and user-friendly dashboard UI utilizing interactive slicers, cards, bar charts, donut charts, and matrix tables.

---

## 🖥️ Dashboard Features

* **KPI Cards:** Instant high-level view of Sales, Profit, Quantity, and AOV.
* **Monthly Trends:** Line/Bar charts visualizing monthly revenue fluctuations.
* **State-wise Breakdown:** Geographical analysis of sales across different Indian states.
* **Product Analytics:** Sub-category analysis to see which specific items drive the most profit.
* **Payment Mode Analysis:** Donut chart showcasing customer distribution across COD, UPI, Credit Card, and EMI.
* **Interactive Slicers:** Dynamic filters for **Quarters**, **States**, and **Categories** to drill down into specific data points.

---

## 📂 Project Structure

```text
├── Data/
│   ├── Orders.csv            # Raw customer order master data
│   └── Details.csv           # Raw product and transaction details
├── Dashboard/
│   └── Madhav_Ecommerce_Dashboard.pbix  # Main Power BI Desktop file
└── README.md                 # Project documentation (This file)
```

---

## 🚀 How to Run and Link Local Data

Because the data sources are originally mapped to local file paths, follow these steps to run the dashboard on your machine:

1. Download and install **Power BI Desktop** (Free).
2. Clone or download this project repository to your PC.
3. Open the `Madhav_Ecommerce_Dashboard.pbix` file.
4. **Update the Data Source Paths:**
   * In the top Home ribbon, click on **Transform Data** > **Data source settings**.
   * Select `Orders.csv`, click **Change Source**, and browse to where you saved the file on your PC.
   * Do the exact same step for `Details.csv`.
   * Click **Close & Apply** to refresh the dashboard with the newly mapped paths.

---

### 🎨 Dashboard Preview
<!-- Yahan apne dashboard ka screenshot drag & drop karke upload kar dein -->
![Dashboard Screenshot](https://github.com)

---

### 🔗 Live Interactive Link
* 🌐 **[View Live Interactive Dashboard](https://powerbi.com)** 
*(Note: Live link ke liye Power BI desktop me **File -> Publish to web (public)** karke link nikalna hoga).*

---
---

## 🤝 Contributing & Feedback

If you have any suggestions to optimize the DAX queries, improve the UI/UX design, or add advanced forecasting models, feel free to open an issue or submit a pull request!

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
