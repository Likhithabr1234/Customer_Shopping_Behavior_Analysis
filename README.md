# Customer_Shopping_Behavior_Analysis
Data Analysis Project Customer Shopping Behavior Analysis using Python, SQL, Power BI.
📊 Customer Shopping Behavior Analysis

This project analyzes customer purchasing patterns using Python, SQL, and Power BI. The goal is to uncover insights related to spending habits, product preferences, customer segmentation, and factors influencing purchase behavior.

The end-to-end pipeline includes data cleaning, exploratory data analysis, business queries using SQL, and an interactive Power BI dashboard for visualization.

🗂️ 1. Project Overview

This project focuses on understanding customer shopping behavior using a dataset containing 3,900 purchase transactions across multiple categories.
The analysis provides insights useful for:

Marketing strategy

Product recommendations

Customer retention programs

Business decision-making

📁 2. Dataset Summary

Dataset Size:

Rows: 3,900

Columns: 18

Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Amount, Size, Color, Season

Shopping Behavior: Discount Applied, Promo Code, Previous Purchases, Frequency

Review & Shipping: Review Rating, Shipping Type

Missing Data: 37 missing values in Review Rating (handled during cleaning)

🐍 3. Exploratory Data Analysis (Python)

The EDA and preprocessing were performed using Python.

✔️ Key Steps:

Data Loading: Imported using Pandas

Initial Inspection: df.info(), df.describe()

Missing Values: Imputed Review Rating using category-wise median

Column Standardization: Converted column names to snake_case

Feature Engineering:

age_group (binned age brackets)

purchase_frequency_days

Redundancy Check: Removed duplicate fields such as promo_code_used

Database Integration: Loaded cleaned data into PostgreSQL for SQL analysis

🧮 4. SQL Analysis (PostgreSQL)

Structured queries were used to answer business-critical questions.

🔍 Key Insights:

Revenue by Gender: Compared revenue contribution of male vs. female customers

High-Spending Discount Users: Identified customers who used discounts but still spent above average

Top-Rated Products: Extracted top 5 products based on average review ratings

Shipping Type Comparison: Compared average purchase amounts for Standard vs Express

Subscriber vs Non-Subscriber Behavior: Revenue and average spend comparison

Discount-Dependent Products: Found items most frequently purchased with discounts

Customer Segmentation: Categorized customers into New, Returning, Loyal

Top Products per Category: Extracted top 3 items in every category

Repeat Buyers & Subscriptions: Checked correlation between loyalty and subscription

Revenue by Age Group: Identified high-value age segments

📊 5. Power BI Dashboard

An interactive dashboard was built to visualize:

Revenue trends

Customer segments

Shipping preferences

Top products

Category performance

Discount impact on purchases

This helps stakeholders make data-driven decisions efficiently.

📝 6. Business Recommendations

Based on the findings, the following strategic actions were suggested:

Boost Subscriptions: Offer incentives and exclusive benefits

Loyalty Programs: Reward frequent buyers to increase retention

Optimize Discounts: Balance margins while attracting price-sensitive buyers

Product Positioning: Highlight high-rated and best-selling items

Targeted Marketing: Focus on profitable age groups and express shipping users

📦 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/                     # Raw and cleaned dataset
├── notebooks/                # Python EDA Notebook
├── sql_queries/              # PostgreSQL business queries
├── dashboard/                # Power BI file
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies

🚀 Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

PostgreSQL

Power BI

Jupyter Notebook
