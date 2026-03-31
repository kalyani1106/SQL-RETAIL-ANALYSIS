##🚀 SQL Retail Sales Analytics Project

This project demonstrates a complete end-to-end SQL workflow using a retail sales dataset.
It simulates real-world business scenarios and solves them using SQL queries.

#💡 Project Objective

To analyze retail business data and generate insights such as:

Identifying top customers
Understanding purchasing behavior
Detecting high-value transactions
Analyzing trends and performance
#🧱 Database Schema

The project includes the following tables:

customers – customer details
stores – store information
products – product categories
sales – transactional data
#⚙️ Data Generation
Generated 1000+ sales records using Oracle SQL
Used functions like DBMS_RANDOM, CONNECT BY, and MOD
Simulated realistic transactional data
#📊 Project Workflow
#1️⃣ Data Understanding

Business Goal: Analyze overall performance

Total transactions
Total revenue
Unique customers
Average order value
Quantity sold
Sales per store/category
Daily transactions
#2️⃣ Data Cleaning

Business Goal: Handle missing and inconsistent data

Replace NULL values using NVL, COALESCE, NVL2
Calculate net revenue
Identify missing data
Create cleaned dataset
#3️⃣ Filtering (WHERE)

Business Goal: Extract specific insights

Sales in last 30 days
High-value transactions
Store/category-based filtering
Recent transactions
#4️⃣ Aggregation (GROUP BY)

Business Goal: Segment business performance

Revenue per store/category/customer
Monthly & daily revenue
Total quantity & discounts
Transaction counts
#5️⃣ HAVING Clause

Business Goal: Identify top performers

High revenue customers
Top stores
High growth categories
Frequent buyers
#6️⃣ CASE WHEN (Business Logic)

Business Goal: Categorize and segment data

Customer segmentation (High/Medium/Low)
Transaction classification
Revenue-based store segmentation
Custom labels for reporting
#7️⃣ Joins (Multi-table Analysis)

Business Goal: Combine data across tables

Customer + Sales + Store insights
Category-wise revenue
Cross-store purchases
Missing data detection
#8️⃣ Window Functions

Business Goal: Advanced analytics

Ranking customers
Running totals
LAG & LEAD comparisons
Moving averages
Growth analysis
#9️⃣ NTILE / Segmentation

Business Goal: Customer segmentation

Top 25% customers
Bottom 25% customers
Quartile analysis
Marketing segments
#🔟 FIRST_VALUE / LAST_VALUE

Business Goal: Compare best vs worst

Highest & lowest sales
Best customer per store
Category performance comparison
#1️⃣1️⃣ Date Analysis

Business Goal: Time-based insights

Daily & monthly sales
Weekend analysis
Sales growth trends
Repeat customers
#🔥 Key Highlights
120+ SQL queries
Covers beginner → advanced concepts
Real-world business problem solving
Strong focus on analytics & insights
Includes window functions and segmentation
#🛠️ Technologies Used
Oracle SQL
SQL Developer
#📁 Project File
SQL-RETAIL-SALES-ANALYSIS.pdf → Complete queries with outputs
#💯 Conclusion

This project helped in understanding how SQL is used in real-world scenarios — from raw data to meaningful business insights.
