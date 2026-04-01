📊 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to extract meaningful insights about customer patterns, preferences, and subscription behavior to support business decision-making.

📂 Dataset Summary
Total Records: 3,900
Total Features: 18
Key Attributes:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item, Category, Amount, Season, Size, Color
Behavior Metrics: Discounts, Promo Codes, Previous Purchases, Ratings, Shipping Type
Missing Values: 37 values in the Review Rating column
🧹 Data Preprocessing (Python)
Data loading using Pandas
Handling missing values using median imputation
Feature engineering:
Created age groups
Derived purchase frequency
Standardized column names (snake_case)
Removed redundant columns (e.g., promo_code_used)
Loaded cleaned data into PostgreSQL for analysis
🛠️ SQL Analysis (Key Business Questions)
Revenue comparison by gender
Identification of high-spending discount users
Top-rated products
Shipping type vs purchase behavior
Subscribers vs non-subscribers analysis
Discount-dependent products
Customer segmentation (New, Returning, Loyal)
Top products by category
Repeat buyers vs subscription behavior
Revenue by age group
📈 Key Insight (Your Question)

Customers with more than 5 previous purchases were analyzed to determine subscription behavior.
As shown in the results (page 6), a large portion of repeat buyers are not subscribed, indicating that repeat purchases do not necessarily guarantee subscription conversion.

📊 Dashboard (Power BI)

An interactive dashboard was created to visualize:

Customer distribution
Revenue trends
Subscription insights
Sales by category and age group
💡 Business Recommendations
Improve subscription strategies with exclusive benefits
Introduce loyalty programs for repeat customers
Optimize discount strategies
Focus on high-performing products
Target marketing based on customer segments
🧰 Tools & Technologies
Python (Pandas, NumPy)
PostgreSQL (SQL Analysis)
Power BI (Dashboard Visualization)
🚀 Conclusion

This project demonstrates how data analysis can uncover customer behavior patterns and provide actionable insights for improving business strategies, especially in customer retention and subscription growth.
