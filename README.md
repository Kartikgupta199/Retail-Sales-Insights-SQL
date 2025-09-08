📖 **Project Overview**

This project analyzes a retail sales database using SQL to generate key business insights. The workflow includes data cleaning, handling missing values, outlier treatment, and fixing inconsistencies across tables. It then performs exploratory data analysis (EDA) to study:
-Sales trends (monthly, quarterly, MoM growth)
-Customer purchase behavior
-Product performance
-Regional insights

The project highlights how SQL can transform raw retail data into actionable insights for data-driven decision-making.

⚙️ **Data Cleaning Steps**
-Replaced missing/blank values in customer location with the most frequent value
-Standardized date formats across tables
-Removed duplicate sales transactions
-Fixed price mismatches between sales and products tables
-Treated outliers (e.g., incorrect ages like 131)

📊 **Exploratory Data Analysis (EDA)**
-**Product Performance**
  -Identified top-selling products & categories by units and revenue
  -Highlighted underperforming products
-**Sales Trends**
  -Analyzed monthly & quarterly sales
  -Calculated **Month-over-Month (MoM)** growth using SQL window functions
-**Customer Profiling**
  -Segmented customers by age group, gender, purchase frequency, and spending
  -Identified loyal customers, high spenders, and occasional buyers
-**Regional Insights**
  -Found the West region leads in sales
  -East region has potential for targeted growth strategies

💡 **Key Insights**

-Old-age customers generate the highest revenue, while adults spend the least
-Product 17 is a top-performing product
-West region drives maximum sales; East shows scope for expansion
-Loyal customers with 10+ transactions & >₹2000 spend are highly valuable

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
