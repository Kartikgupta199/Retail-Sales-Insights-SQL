# 🛒 Retail Sales Analysis using SQL  

## 📖 Project Overview  
This project analyzes a **retail sales database** using **SQL** to deliver actionable business insights.  

**Workflow covers:**  
- 🧹 **Data Cleaning** → handling nulls, fixing inconsistencies, removing duplicates & outliers  
- 📊 **Exploratory Data Analysis (EDA)** → sales trends, customer profiling, product performance, regional insights  
- 📈 **Business Insights** → customer segmentation, loyalty analysis, revenue growth drivers  

---

## ⚙️ Data Cleaning  
- ✅ Replaced missing/blank values in `customers` table  
- ✅ Standardized date formats across tables  
- ✅ Removed duplicate sales transactions (`TransactionID`)  
- ✅ Fixed price mismatches between `sales` & `products`  
- ✅ Treated outliers (e.g., unrealistic ages like `131`)  

---

## 📊 Exploratory Data Analysis  

**🔹 Product Performance**  
- Identified **top-selling products** by units & revenue  
- Found **underperforming products & categories**  
**🔹 Sales Trends**  
- Monthly & quarterly sales analysis  
- **Month-over-Month (MoM) growth** using SQL window functions  
**🔹 Customer Profiling**  
- Segmented by **age group, gender, purchase frequency, spending**  
- Identified **loyal customers** & **occasional buyers**  
**🔹 Regional Insights**  
- **West region** → highest revenue  
- **East region** → low sales, growth potential  
---
## 💡 Key Insights  
- 👴 Old-age customers contribute the **highest revenue**  
- 🏆 **Product 17** is the top-performing product  
- 📍 **West region** dominates sales; **East region** needs focus  
- 🔁 Loyal customers with **10+ transactions & >2000 revenue** are most valuable  
---
## 🛠️ SQL Concepts Used  


-- Data Cleaning
UPDATE, DELETE, ALTER, JOIN  
-- Aggregations
SUM(), COUNT(), ROUND()  
-- Date Functions
STR_TO_DATE(), DATEDIFF(), DATE_FORMAT(), EXTRACT()  
-- Window Functions
LAG() OVER (ORDER BY ...)  
-- Customer Segmentation
CASE WHEN logic

---
## 📂 Dataset  
- **The project uses 3 main tables:** 
- 👥 Customers → demographics & join dates  
- 📦 Products → categories & prices  
- 🧾 Sales → transaction-level purchase details  

---
## 🚀 Outcomes
-✔ Cleaned & standardized dataset
-✔ Built monthly & quarterly sales trend reports
-✔ Profiled customer segments for marketing
-✔ Delivered insights for revenue growth & expansion
