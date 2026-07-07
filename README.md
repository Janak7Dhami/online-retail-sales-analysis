# 🛒 Online Retail Sales Analysis

**An end-to-end data analytics project** — from raw transactional data to actionable business insights — using **Python (Pandas)**, **SQL**, and **Power BI**.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Planned-lightgrey?logo=postgresql)
![Power BI](https://img.shields.io/badge/Power%20BI-Planned-lightgrey?logo=powerbi)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## 📌 Overview

This project analyzes **over 700,000 retail transactions** from the **Online Retail II** dataset to uncover patterns in sales performance, customer behavior, and product trends.

This is being built as a complete, end-to-end data analytics project. **Currently completed:** data cleaning and exploratory data visualization in Python. **Coming next:** deeper business analysis using SQL (including RFM customer segmentation) and an interactive Power BI dashboard.

The goal is to simulate a real-world business analytics task: turning messy, unstructured transactional data into clear, decision-ready insights for a retail business.

---

## 🎯 Business Objectives

- Identify top-performing products, categories, and regions by revenue
- Segment customers using **RFM (Recency, Frequency, Monetary)** analysis to find high-value customers
- Uncover seasonal and time-based sales trends to support inventory and marketing planning
- Detect and quantify the impact of order cancellations/returns on net revenue
- Present findings through an interactive dashboard usable by non-technical stakeholders

---

## 🗂️ Dataset

- **Source:** [Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii) (UCI Machine Learning Repository)
- **Size:** ~700,000+ transaction records
- **Period:** December 2009 – December 2011
- **Description:** Transactional data for a UK-based online retailer selling unique all-occasion gift items, including invoice number, stock code, product description, quantity, invoice date, unit price, customer ID, and country.

---

## 🛠️ Tech Stack

| Stage | Tools Used | Status |
|---|---|---|
| Data Cleaning & Preprocessing | Python, Pandas, NumPy | ✅ Done |
| Exploratory Data Analysis & Visualization | Python (Pandas, Matplotlib/Seaborn) | ✅ Done |
| Business Analysis & Segmentation | SQL (RFM Analysis) | 🔜 Planned |
| Interactive Dashboard | Power BI | 🔜 Planned |
| Version Control | Git & GitHub | ✅ Done |

---

## 🔄 Project Workflow

```
Raw Dataset (Online Retail II)
        │
        ▼
1. Data Cleaning (Python/Pandas)  ✅ Done
   - Handle missing CustomerIDs
   - Remove duplicates & cancelled orders
   - Fix data types (dates, IDs, prices)
   - Create derived columns (e.g., TotalPrice)
        │
        ▼
2. Exploratory Data Visualization (Python)  ✅ Done
   - Sales trends over time
   - Top products & countries by revenue
   - Distribution and outlier analysis
        │
        ▼
3. SQL Analysis  🔜 Planned
   - Revenue & sales trend queries
   - RFM (Recency, Frequency, Monetary) segmentation
   - Customer & product-level aggregations
        │
        ▼
4. Power BI Dashboard  🔜 Planned
   - Interactive visuals for sales, customers & products
   - KPI cards, trend lines, and segment breakdowns
```

---

## 📊 Key Insights (So Far)

> *Update this section with the specific figures from your notebook.*

- Identified and handled missing `CustomerID` values, duplicate records, and cancelled/returned orders during cleaning
- Corrected data types (e.g., `InvoiceDate` to datetime, `CustomerID` to string) to enable reliable time-based and customer-level analysis
- Initial visualizations reveal **[top-selling products/categories]** and **[peak sales periods]** — add specifics here
- **[Country/Region]** shows the highest order volume outside the UK

> 🔜 Deeper insights — customer segmentation (RFM), revenue drivers, and cross-metric analysis — will be added once the SQL analysis stage is complete.

---

## 📈 Visualizations

All charts, plots, and dashboard visuals are generated and displayed directly within **`online_retail_analysis.ipynb`** as part of the analysis — no separate image files needed. Open the notebook on GitHub (it renders inline) or run it locally to view:

- Revenue trends over time
- Top products/categories by sales
- Customer segmentation (RFM) visuals
- Power BI dashboard screenshots embedded in the final section

---

## 📁 Repository Structure

```
online-retail-sales-analysis/
│
├── online_retail_analysis.ipynb   # Full data cleaning + EDA + SQL analysis + visuals
└── README.md                      # Project documentation
```

---

## 🚀 How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Janak7Dhami/online-retail-sales-analysis.git
   cd online-retail-sales-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook online_retail_analysis.ipynb
   ```

4. **Explore the dashboard**
   - Power BI dashboard visuals are included as screenshots directly within the notebook. If a `.pbix` file is included in the repo, open it in Power BI Desktop for the fully interactive version.

---

## 🔮 Roadmap

- [ ] **SQL Analysis** — revenue queries, RFM (Recency, Frequency, Monetary) customer segmentation, product-level aggregations
- [ ] **Power BI Dashboard** — interactive visuals with KPI cards, trend lines, and segment breakdowns
- [ ] Customer lifetime value (CLV) estimation
- [ ] Deploy the Power BI dashboard to Power BI Service for live sharing

---

## 👤 Author

**Janak Gurudhami (Jack)**
Final-year B.Tech CSE student | Aspiring Data Analyst
📍 Bengaluru, India

- GitHub: [@Janak7Dhami](https://github.com/Janak7Dhami)

---

⭐ If you found this project useful or interesting, consider giving it a star!
