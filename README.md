# 🚚 Olist Logistics Performance Command Center

### End-to-End Logistics Analytics | Delivery Reliability & Seller Health (Brazilian E-Commerce)

## 📌 Project Overview

- This project is an **end-to-end logistics analytics solution** built on a real-world Brazilian e-commerce dataset.
It focuses on **delivery reliability, seller performance, and operational risk**, designed from the perspective of a **Data Analyst / Business Analyst supporting operations teams**.

The goal of this project is not just visualization, but **actionable decision-making** — helping logistics and marketplace teams identify **high-impact problem areas** and prioritize interventions.

## 🎯 Business Problem

- Large e-commerce marketplaces face recurring challenges such as:

* High late-delivery rates
* Inconsistent seller performance
* Difficulty identifying *which sellers* drive most logistics delays
* Limited visibility into delivery performance across regions

### Key Business Questions Answered

- Which sellers contribute disproportionately to late deliveries?
- Are delivery delays driven by order volume or operational inefficiency?
- How does average delivery lead time vary across seller states?
- Which sellers pose the highest operational risk?
- Where should operations teams focus to reduce delays most effectively?

---

**Key question:**

> *How can operations teams reduce late deliveries without chasing every single delay?*

---

## 💡 Key Insight (Executive Summary)

> **80% of logistics delays are driven by just the top 20% of underperforming sellers.**

This Pareto insight enables operations teams to:

* Stop reacting to isolated delays
* Focus on a **small, high-impact seller group**
* Improve delivery reliability with targeted interventions

## 📊 Dashboard Highlights

The Power BI dashboard acts as a **Logistics Command Center**, providing:

### 🔹 Core KPIs

* **Total Orders:** 110K
* **Late Rate:** 7%
* **Average Delivery Time:** 12.41 days
* **Seller Health Score:** 93%

### 🔹 Analytical Views

* **80/20 Pareto Analysis** to identify sellers driving most late orders
* **Delivery Lead Time by Seller State** (regional benchmarking)
* **Order Volume vs Delivery Performance** (operational trade-offs)
* **Year-over-Year Order Growth** (business scale context)

📷 *Dashboard Screenshot:*
`screenshots/final_dashboard.png`

---

## 🛠️ Tech Stack

| Layer                | Tools                  |
| -------------------- | ---------------------- |
| Data Processing      | Python (Pandas, NumPy) |
| Analysis Environment | Jupyter Notebook       |
| Querying             | SQL (SQLite)           |
| Visualization        | Power BI               |
| Version Control      | Git & GitHub           |

---

## 🧠 Metrics Definitions

* **Late Rate %**
  Percentage of orders delivered after the estimated delivery date.

* **Average Delivery Time (Days)**
  Days between `order_purchase_timestamp` and `order_delivered_customer_date`.

* **Seller Health Score**
  Composite indicator based on delivery timeliness and consistency (higher = better reliability).

---

## 📂 Project Structure

```
olist-logistics-performance/
│
├── Notebook/
│   └── 01_data_ingestion_and_cleaning.ipynb
│
├── scripts/
│   └── business_queries.sql
│
├── data/
│   ├── raw datasets
│   ├── cleaned datasets
│   └── SQLite databases
│
├── screenshots/
│   └── final_dashboard.png
│
├── requirements.txt
└── README.md
```

---

## 🔍 End-to-End Workflow

1. **Data Cleaning & Validation**

   * Cleaned messy real-world data using Pandas & NumPy
   * Validated dates, missing values, and delivery timelines

2. **SQL Analytics**

   * Created operational metrics using SQL queries
   * Structured insights for dashboard consumption

3. **Business-Focused Visualization**

   * Designed executive-level Power BI visuals
   * Focused on *decision clarity*, not visual clutter

---

## 📈 Impact & Use Cases

This dashboard can be used by:

* **Operations Managers** → Identify high-risk sellers
* **Logistics Teams** → Reduce late deliveries efficiently
* **Business Analysts** → Monitor fulfillment health
* **Leadership** → Track operational performance at scale

---

## 🚀 Why This Project Stands Out

✔ Real-world dataset used by industry
✔ End-to-end ownership (data → insights → dashboard)
✔ Business-first storytelling (not tool-centric)
✔ Clear operational recommendations
✔ Portfolio-ready and recruiter-friendly

---

## 👤 Author

**Manas Paliwal**
Aspiring **Data Analyst / Business Analyst**
Open to **internships in India and remote/global roles**

📬 *Feel free to connect or request access to the Power BI file.*

---

## 📚 Data Source & References

* **Olist Brazilian E-Commerce Dataset (Public)**
  Kaggle: [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

* Dataset originally published by **Olist** for research and analytics use.

---

## ⭐ Final Note for Recruiters

This project demonstrates:

* Analytical thinking
* Business problem framing
* SQL + Python proficiency
* Dashboard storytelling
* Independent project ownership

If you’re looking for someone who can **translate data into decisions**, this project reflects exactly that.
