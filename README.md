📖 Project Overview

This project analyzes a retail sales database using SQL to deliver actionable business insights.
The workflow covers:

🧹 Data Cleaning → handling nulls, fixing inconsistencies, removing duplicates & outliers
📊 Exploratory Data Analysis (EDA) → sales trends, customer profiling, product performance, regional insights
📈 Business Insights → customer segmentation, loyalty analysis, revenue growth drivers

⚙️ Data Cleaning

✔ Replaced missing/blank values in customers table
✔ Standardized date formats across tables
✔ Removed duplicate sales transactions (TransactionID)
✔ Fixed price mismatches between sales & products
✔ Treated outliers (e.g., unrealistic ages like 131)

📊 Exploratory Data Analysis
🔹 Product Performance
  Identified top-selling products by units & revenue
  Found underperforming products & categories
🔹 Sales Trends
  Monthly & quarterly sales patterns
  Month-over-Month (MoM) growth using LAG() window function
🔹 Customer Profiling
  Segmented by age group, gender, purchase frequency, spending
  Identified loyal customers & occasional buyers
🔹 Regional Insights
  West region → highest revenue
  East region → low sales, potential for growth

💡 Key Insights

📌 Old-age customers contribute the highest revenue
📌 Product 17 is the top-performing product
📌 West region dominates sales; East needs focus
📌 Loyal customers with 10+ transactions & >2000 revenue are most valuable

🛠️ **SQL Concepts Used**

-Data Cleaning → UPDATE, DELETE, ALTER, JOIN
-Aggregations → SUM(), COUNT(), ROUND()
-Date Functions → STR_TO_DATE(), DATEDIFF(), DATE_FORMAT(), EXTRACT()
-Window Functions → LAG() for MoM growth
-Customer Segmentation → CASE WHEN logic

📂 **Dataset**

The project uses 3 main tables:
Customers → Customer demographics & join dates
Products → Product catalog with categories & prices
Sales → Transaction-level purchase details

🚀 **Outcomes**

✔ Improved dataset quality through cleaning & transformation
✔ Generated sales trend reports (monthly & quarterly)
✔ Profiled customer segments for marketing strategies
✔ Delivered actionable insights for revenue growth & regional expansion

📌 How to Run the Project

-Create a database in MySQL (e.g., Retail)
-Import tables: customers, products, sales
-Run the SQL scripts in sequence:
  -Data Cleaning
  -EDA Queries
  -Customer Profiling & Segmentation

🔗 Author

👤 Kartik Gupta
💼 Aspiring Data Analyst
🔎 Focused on SQL, Python, Excel, and Power BI
