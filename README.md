# 🪙 Financial Performance Dashboard (Tableau)

An **interactive Financial Performance Dashboard** built using **Tableau**, designed to analyze business performance across **countries, products, segments, and time periods**.
The project focuses on key financial metrics such as **Revenue, Sales, Profit, Discounts, and Profit Margin**, supported by **Python-based data cleaning** to simulate a real-world analytics workflow.

---

## 🎯 Project Objective

The objective of this project is to:

* Analyze **financial performance** across multiple dimensions
* Identify **profitability trends**, **discount impact**, and **country-level performance**
* Enable **data-driven decision-making** through interactive visual analytics

---

## 🛠 Tools & Technologies

* **Tableau Desktop / Tableau Public** – Data visualization & dashboarding
* **Python (Jupyter Notebook)** – Data cleaning & preprocessing
* **Pandas, NumPy** – Data manipulation
* **CSV Dataset** – Financial transaction data

---

## 📂 Project Folder Structure

```
├── Financial Performance Dashboard.png     # Dashboard preview
├── Financial Performance Dashboard.twb     # Tableau workbook
├── README.md                               # Project documentation
│
├── notebook/
│   └── Financial_Data_Cleaning.ipynb       # Python data cleaning notebook
│
└── data/
    ├── cleaned_financial_data.csv          # Cleaned dataset used in Tableau
    └── financial_data.csv                  # Raw dataset
```

---

## 🧹 Data Cleaning & Preparation

Data cleaning was performed using **Python in Jupyter Notebook** to ensure high-quality, analysis-ready data.

### Key Cleaning Steps:

* Removed currency symbols (`$`) and commas from numeric fields
* Converted financial columns to numeric data types
* Handled missing and invalid values
* Standardized column names for Tableau compatibility
* Converted date fields to proper datetime format
* Validated financial logic (Sales, COGS, Discounts, Profit)

📘 *Notebook:* `notebook/Financial_Data_Cleaning.ipynb`

---

## 📈 Key KPIs in the Dashboard

* **Total Revenue (Gross Sales)**
* **Total Sales (Net Sales)**
* **Total Profit**
* **Total Discounts**
* **Profit Margin (%)**

These KPIs provide a quick executive-level overview of business performance.

---

## 📊 Dashboard Visualizations

* **Sales & Profit by Country** – Country-wise performance comparison
* **Sales & Profit Trend Over Time** – Monthly and yearly trend analysis
* **Discount Impact Analysis** – Relationship between gross sales and discounts
* **Product Discount Heatmap** – Product performance across discount bands

---

## 🖼️ Dashboard Preview

![Financial Performance Dashboard](Financial%20Performance%20Dashboard.png)

---

## 🌐 Live Dashboard (Tableau Public)

🔗 **View Interactive Dashboard on Tableau Public:**
[Tableau Public :- Financial Performance Dashboard](https://public.tableau.com/views/FinancialPerformanceDashboard_17681446623460/FinancialPerformanceDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

> This live version allows users to explore Financial Performance interactively using Filters.

---

## 🔍 Key Business Insights

* The business achieves a **healthy overall profit margin**, though discounts significantly impact net sales.
* Certain countries consistently outperform others in both sales and profitability.
* High discounts do **not always correlate with higher profits**.
* Some products perform well even with **low or no discounts**, indicating pricing power.
* Seasonal trends show stronger performance in later months of the year.

---

## 🚀 How to Use This Project

1. Review the **data cleaning notebook** to understand preprocessing steps
2. Open the `.twb` file in **Tableau Desktop**
3. Explore interactive filters (Segment, Country, Year, Month, Discount Band)
4. Analyze financial performance and derive insights
