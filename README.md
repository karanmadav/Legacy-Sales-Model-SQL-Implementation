# 🧮 Legacy Sales SQL Project

This project demonstrates practical SQL skills using the **Legacy Sales Model**, a retail-themed schema that includes orders, customers, products, employees, and payments. The queries explore business logic, segmentation, sales insights, data modeling, views, stored procedures, triggers, and advanced analytics.

---

## 📂 Project Files

- `Legacy Sales Model.sql` → All 13 query solutions with advanced SQL logic
- `sample_outputs.xlsx` → Output of key queries (optional)

---

## 📊 Key Insights

### 🧑‍💼 Employee & Product Queries
- Extracted Sales Reps reporting to a specific manager
- Identified product lines containing “Cars” using `LIKE`

### 🌎 Customer Segmentation & Region Logic
- Segmented customers into **North America, Europe, Others** using `CASE`  
- Helps define regional business strategies and comparisons

### 📈 Sales & Order Analysis
- Top 10 most-ordered products based on `quantityOrdered`
- Detected months with high payment activity (>20), useful for trend spotting

### 🛠️ Table Creation & Constraints
- Created normalized `Customers` and `Orders` tables with:
  - `PRIMARY KEY`, `FOREIGN KEY`, and `CHECK` constraints
  - Ensured quality and referential integrity

### 🌍 Country-wise Order Distribution
- Listed **top 5 countries** by order volume using `JOIN` and `GROUP BY`

### 🔁 Manager-Employee Hierarchy
- Used **self-join** to display reporting relationships from a single table

### 👁️‍🗨️ View for Category Performance
- Created view `product_category_sales` showing:
  - Total sales by product line
  - Distinct orders count per category

### 🧮 Stored Procedures with Parameters
- Procedure `Get_country_payments(year, country)` calculates:
  - Year-wise country payments with dynamic parameters

### 🪜 Ranking & Year-over-Year Analysis
- Used `DENSE_RANK()` to rank customers by order frequency  
- Used `LAG()` and CTE to calculate **% change YoY** in monthly orders

### 💸 Price-Based Filtering
- Filtered product lines with **above-average buying price** using subqueries

### ⚠️ Error-Handled Insert Procedure
- Created procedure with `EXIT HANDLER` to show user-friendly error messages

### 🔄 Data Correction with Trigger
- Trigger `trg_BeforeInsert_PositiveHours` auto-converts **negative hours to positive** before insert

---

## 🛠️ Tools & Technologies

| Tool             | Purpose                      |
|------------------|------------------------------|
| MySQL Workbench  | Query execution, procedures  |

---

## 📅 Duration

**March 2025 – June 2025**

---

## 👨‍💻 Author

**Karan Madav**  
*Aspiring Data Analyst | Skilled in MySQL, Excel, Power BI, Tableau*  
[LinkedIn](https://www.linkedin.com/in/karan-madav) 



