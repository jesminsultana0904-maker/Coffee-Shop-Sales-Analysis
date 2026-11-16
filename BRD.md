# Business Requirements Document (BRD)
**Project Title:** Coffee Shop Sales Analysis  
**Project Type:** Capstone Project  
**Prepared By:** Akshay, Sufiyan Khan, Jatin Tripathi, Mukasma Parbeen, Jesmin Sultana  
**Role:** Data Analyst  
**Submitted To:** Anshul Gautam  
**Submission Date:** July 8, 2026  

---

## 1. Document Overview
This Business Requirements Document (BRD) outlines the objectives, scope, and requirements for the **Coffee Shop Sales Analysis Dashboard**. The dashboard aims to analyze sales performance, product trends, and store operations to support data-driven business decisions such as menu optimization, pricing strategies, inventory planning, and promotional activities.

---

## 2. Business Problem Statement
The coffee shop lacks a structured way to analyze its sales data and identify opportunities for business improvement. Management needs insights into product performance, store performance, customer purchasing trends, new ideas, and peak sales periods to make better decisions and improve overall profitability.

---

## 3. Business Goals
The primary goals of this project are to:
* Increase overall sales revenue through data-driven decision-making.
* Identify top-performing and underperforming products for menu optimization.
* Analyze sales trends across stores, product categories, and time periods.
* Improve inventory planning by understanding product demand.
* Evaluate store performance to identify opportunities for operational improvement.
* Support pricing and promotional strategies using sales insights.
* Enable management to monitor Key Performance Indicators (KPIs) through an interactive dashboard.

---

## 4. Stakeholders

| Stakeholder | Role | Business Need |
| :--- | :--- | :--- |
| **Business Owner** | Decision Maker | Monitor overall business performance and profitability. |
| **Sales Manager** | Sales Analysis | Monitor sales trends, product performance, and revenue growth. |
| **Marketing Team** | Promotions | Identify products for promotions and evaluate campaign opportunities. |
| **Inventory Manager** | Inventory Planning | Forecast product demand and optimize stock levels. |

---

## 5. Business Requirements

### 5.1 Functional Requirements
The dashboard must:
* Display key business metrics such as Total Sales, Total Orders, Total Quantity Sold, and Average Order Value.
* Analyze sales performance across different store locations.
* Show sales trends by day, month, and hour.
* Compare the performance of product categories and individual products.
* Identify top-selling and low-performing menu items.
* Provide interactive filters for date, store location, product category, and product type.
* Enable users to monitor business performance through interactive visualizations.
* Support decision-making for menu optimization, promotions, staffing, and inventory planning.

### 5.2 Non-Functional Requirements
The dashboard must:
* Be easy to understand and user-friendly.
* Display accurate and consistent data.
* Allow quick filtering and navigation.
* Present information through clear and interactive visualizations.
* Refresh data when new transaction data is available.
* Maintain a clean and professional dashboard layout.

---

## 6. Data Overview
The project uses a **Coffee Shop Sales Transaction** dataset containing transactional records from multiple store locations. Each record represents a single sales transaction and includes information about the transaction date and time, store location, products sold, quantity purchased, and unit price.

### Dataset Fields

| Field Name | Description |
| :--- | :--- |
| `transaction_id` | Unique identifier for each transaction |
| `transaction_date` | Date on which the transaction occurred |
| `transaction_time` | Time of the transaction |
| `transaction_qty` | Quantity of products purchased |
| `store_id` | Unique identifier for the store |
| `store_location` | Location of the store (Astoria, Hell's Kitchen, Lower Manhattan) |
| `product_id` | Unique identifier for the product |
| `unit_price` | Price of one unit of the product |
| `product_category` | Category of the product (e.g., Coffee, Tea, Bakery) |
| `product_type` | Type of product within a category |
| `product_detail` | Detailed name or description of the product |

### Data Scope
* **Data Type:** Sales transaction data
* **Primary Purpose:** To analyze sales performance, product demand, store performance, and time-based sales trends.

---

## 7. Key Performance Indicators (KPIs)
* **Total Revenue**
* **Total Orders**
* **Total Quantity Sold**
* **Average Order Value (AOV)**
* **Average Selling Price (ASP)**
* **Top Selling Product / Category**
* **Top Performing Store**

---

## 8. Business Questions

### Sales Performance
* What is the total sales revenue generated?
* How many orders and products have been sold?
* How do sales vary over different days, weeks, and months?

### Menu & Product Performance
* Which products are the best-selling and highest-revenue generators?
* Which products have the lowest sales and may require menu updates or discontinuation?
* Are there products that could benefit from promotional campaigns?

### Store Performance
* Which store location generates the highest sales and revenue?
* Which stores are underperforming and require operational improvements?
* How does sales performance compare across different locations?

### Time-Based Analysis
* During which hours of the day are sales the highest?
* Which days of the week experience the highest customer demand?
* Are there seasonal or monthly sales trends?

### Business Decision-Making
* Which menu items should be retained, promoted, or removed?
* Where should promotional campaigns be focused?
* How can staffing and inventory be optimized based on sales patterns?
* What opportunities exist to increase overall revenue and improve operational efficiency?

---

## 9. Dashboard Requirements
The Coffee Shop Sales Dashboard provides an interactive and user-friendly interface enabling stakeholders to monitor sales performance and make informed business decisions.

### Dashboard Components
* **KPI Cards:** Total Revenue, Total Orders, Total Quantity Sold, Average Order Value, Average Selling Price, Top Performing Store.
* **Visualizations:**
  * Sales Trend (Daily / Monthly)
  * Sales by Store Location
  * Sales by Product Category
  * Top & Bottom Performing Product Categories
  * Sales by Hour of the Day
  * Sales by Day of the Week
* **Filters (Slicers):** Transaction Date, Store Location, Product Category, Product Type, Product Detail.

---

## 10. Business Rules
The following business rules apply during data analysis and dashboard development:
1. **Total Sales** is calculated as: $\text{Transaction Quantity} \times \text{Unit Price}$
2. Each `transaction_id` represents a unique customer transaction.
3. **Total Orders** is calculated by counting unique `transaction_id` values.
4. **Total Quantity Sold** is calculated by summing `transaction_qty`.
5. **Average Order Value (AOV)** is calculated as: $\frac{\text{Total Sales}}{\text{Total Orders}}$
6. **Average Selling Price (ASP)** is calculated as: $\frac{\text{Total Revenue}}{\text{Total Quantity Sold}}$
7. **Store Performance** is evaluated based on total sales revenue and order volume.
8. **Product Performance** is measured using sales revenue and quantity sold.
9. **Time-Based Analysis** is performed using `transaction_date` and `transaction_time` to identify peak hours and high-demand days.
10. **Data Quality Assumption:** The dataset is assumed to be complete, accurate, and free from duplicate or invalid transaction records.

---

## 11. Expected Insights
* Identifying top-performing and underperforming products for menu optimization.
* Understanding which product categories contribute the most to sales and revenue.
* Comparing store performance to identify high-performing and underperforming locations.
* Analyzing sales trends across different days, months, and time periods.
* Identifying peak business hours to optimize staff scheduling.
* Understanding product demand to improve inventory planning and reduce stockouts or overstocking.
* Identifying opportunities for promotional campaigns based on product and sales trends.

---

## 12. Success Criteria
The project is considered successful if the dashboard:
* Accurately displays all key KPIs.
* Provides clear insights into sales, products, stores, and time-based trends.
* Supports data-driven decisions for menu optimization, promotions, and inventory planning.
* Includes interactive filters for dynamic self-service analysis.
* Presents information through clean, accessible, and user-friendly visualizations.

---

## 13. Appendix

### A. Data Source
* Coffee Shop Sales Transaction Dataset

### B. KPI Formulas
* $\text{Total Revenue} = \sum (\text{Transaction Quantity} \times \text{Unit Price})$
* $\text{Total Orders} = \text{COUNT}(\text{Transaction ID})$
* $\text{Average Selling Price} = \frac{\text{Total Revenue}}{\text{Total Quantity Sold}}$
* $\text{Average Order Value} = \frac{\text{Total Sales}}{\text{Total Orders}}$

### C. Abbreviations
* **BRD:** Business Requirements Document
* **KPI:** Key Performance Indicator
* **BI:** Business Intelligence
* **AOV:** Average Order Value
* **ASP:** Average Selling Price