# Customer_behavior_analysis
📊 Customer Shopping Behavior Analysis
🔍 Overview

This project analyzes customer shopping behavior using transactional data to uncover patterns in spending, product preferences, and customer segmentation. The objective is to generate actionable insights that support business decision-making and improve customer engagement strategies.

📁 Dataset
Total Records: 3,900 transactions
Features: 18 columns including customer demographics, purchase details, and behavioral metrics
Key Attributes:
Demographics: Age, Gender, Location, Subscription Status
Purchases: Product, Category, Amount, Season
Behavior: Discounts, Frequency, Ratings, Shipping Type
Data Quality: 37 missing values in review ratings handled during preprocessing
🛠️ Tools & Technologies
Python: Pandas, NumPy, Matplotlib, Seaborn
SQL: PostgreSQL
Power BI: Dashboard development
Gamma: Presentation creation
Jupyter Notebook / VS Code
⚙️ Project Steps
1. Data Loading & Exploration
Loaded dataset using Pandas
Performed initial analysis using .info() and .describe()
2. Data Cleaning
Imputed missing review ratings using median values per category
Standardized column names (snake_case)
Removed redundant columns (e.g., promo_code_used)
3. Feature Engineering
Created age_group for segmentation
Derived purchase_frequency_days for behavioral analysis
4. SQL Analysis

Performed business-focused queries in PostgreSQL:

Revenue comparison by gender
High-spending discount users
Top-rated products
Shipping type vs purchase behavior
Subscriber vs non-subscriber analysis
Customer segmentation (New, Returning, Loyal)
Revenue by age group
5. Dashboard Development
Built an interactive Power BI dashboard
Included KPIs, filters, and drill-down features for stakeholders
6. Reporting
Summarized insights in a structured report
Created presentation using Gamma
📊 Dashboard
Interactive visualizations for revenue, customer segments, and product trends
Filters for category, demographics, and purchase behavior
Designed for both technical and non-technical stakeholders

📈 Results & Insights
Identified key revenue drivers across customer segments
High-frequency buyers are more likely to subscribe
Discount strategies influence purchasing behavior but require margin optimization
Certain product categories consistently outperform in ratings and sales
💡 Business Recommendations
Promote subscription benefits to increase retention
Implement loyalty programs for repeat customers
Optimize discount strategies to balance revenue and profit
Focus marketing on high-value customer segments and top-performing products
