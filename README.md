# ☕ Coffee Shop Sales Analysis

An end-to-end Business Intelligence and Data Analytics capstone project designed to uncover actionable insights into sales performance, customer purchasing behavior, product trends, and store operations across multiple coffee shop locations.

---

## 📊 Executive Summary & Key KPIs

Based on transactional data spanning January through June across three New York City locations (**Hell's Kitchen**, **Astoria**, and **Lower Manhattan**), the business achieved the following high-level metrics:

* **Total Revenue:** `$699K`
* **Total Orders:** `149K`
* **Total Quantity Sold:** `214K` units
* **Average Order Value (AOV):** `$4.70`
* **Average Selling Price (ASP):** `$3.30`
* **Top Performing Store:** **Hell's Kitchen** (`33.84%` of total revenue)

---

## 🔍 Key Analytical Insights

### 1. Time-Based Performance
* **Hourly Trends:** Sales peak sharply during the morning rush between **8:00 AM and 10:00 AM** (reaching nearly `$90K` at 10:00 AM) and steadily decline after lunchtime, dropping off significantly after **5:00 PM**.
* **Day of the Week:** Revenue remains strong early in the week (peaking on **Monday** at `~$102K`) and gradually decreases toward the weekend (**Saturday** being the lowest at `~$97K`).
* **Monthly Growth:** Revenue is comparatively lower during Q1 (**January–February** hovering just under `$0.1M`), followed by consistent upward momentum throughout Q2, peaking in **June** (`~$0.17M`).

### 2. Product & Category Performance
* **Top Performing Categories:** **Coffee** (`~$0.27M`) and **Tea** (`~$0.20M`) are the primary revenue drivers, followed by **Bakery**, **Coffee Beans**, and **Drinking Chocolate**.
* **Bottom Performing Categories:** **Packaged Chocolate**, **Flavours**, **Loose Tea**, and **Branded** merchandise contribute significantly less to overall revenue.

### 3. Store Location Breakdown
Performance across all three branches is well-balanced, with **Hell's Kitchen** leading slightly:
* **Hell's Kitchen:** `33.84%`
* **Astoria:** `33.23%`
* **Lower Manhattan:** `32.92%`

---

## 💡 Strategic Business Recommendations

* **Afternoon "Happy Hour" (2:00 PM – 6:00 PM):** Introduce targeted afternoon discounts or flash deals to stimulate foot traffic during post-lunch lulls.
* **Strategic Menu Bundling:** Pair high-performing items with slower-moving inventory—such as **Coffee + Bakery (Pastry)** combos or **Bakery + Packaged Chocolate** bundles—to increase Average Order Value (AOV).
* **Q1 Seasonal Promotions:** Combat early-year dips (January–February) with "Buy One, Get One" (BOGO) offers, winter limited-time beverages, and family/group combo packs.
* **Weekend & Delivery Expansion:** Launch weekend loyalty rewards and introduce a home delivery service to boost Saturday/Sunday revenue.
* **Operational Replication:** Audit product delivery workflows, local promotions, and customer preferences at **Hell's Kitchen** and replicate best practices across **Astoria** and **Lower Manhattan**.
* **Customer Feedback Loop:** Implement a lightweight review/feedback mechanism to continuously refine menu offerings and service quality.

---

## 🛠️ Dashboard Architecture & Features

The interactive BI dashboard includes:
* **Executive KPI Cards:** Real-time tracking of Revenue, Orders, Quantity Sold, AOV, ASP, and Top Store.
* **Interactive Slicers:** Filter dynamically by `Transaction Date`, `Store Location`, `Product Category`, `Product Type`, and `Product Detail`.
* **Visualizations:**
  * *Revenue by Hour of the Day* (Area Chart)
  * *Top 5 & Bottom 5 Product Categories by Revenue* (Bar Charts)
  * *Revenue by Store Location* (Donut Chart)
  * *Revenue by Month* (Line Trend)
  * *Revenue by Day of the Week* (Column Chart)

---

## 📂 Repository Structure

```text
├── README.md                     # Project overview, insights, and recommendations
├── BRD.md                        # Formal Business Requirements Document
├── dashboard/                    # Dashboard source files (.pbix / screenshots)
└── data/                         # Dataset documentation / schema reference
```

---

## 👥 Project Team & Credits

* **Prepared By:** Akshay, Sufiyan Khan, Jatin Tripathi, Mukasma Parbeen, Jesmin Sultana
* **Role:** Data Analysts (Capstone Project)
* **Submitted To:** Anshul Gautam