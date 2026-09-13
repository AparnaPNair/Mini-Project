# Mini-Project
🍽️ Zomato Data Analysis Project
🚀 Project Overview

This project delivers a comprehensive analysis of Zomato data to uncover customer behavior, restaurant performance, and revenue trends.
The solution combines data cleaning (Excel) and interactive visualization (Power BI) to generate actionable business insights.
🎯 Business Objective

To enable data-driven decision-making by analyzing:

🔹Customer demographics and spending patterns
🔹Restaurant performance and pricing strategy
🔹Order trends and revenue drivers

🧩 Dataset Description

The analysis is based on three core datasets:

👤 Users: Demographics, income, occupation, and segmentation
🍽️ Restaurants: Cuisine, ratings, pricing, and delivery details
🧾 Orders: Transactions, revenue, quantity, payment, and delivery

🛠️ Tools & Technologies
🔹Microsoft Excel – Data cleaning & preprocessing
🔹Power BI – Data modeling, DAX, and dashboard development
🔧 Data Preparation Highlights (Excel)

✔ Handled missing values using:

🔹Median (numerical fields)
🔹Mode (categorical fields)
🔹Category-based imputation (income by occupation)

✔ Standardized inconsistent data:

🔹Status normalization (Active, Delivered)
🔹Date formatting
🔹Category corrections

✔ Data enrichment:

🔹Created derived features:
🔹Age Group, Income Group, Family Type
🔹Rating Level, Delivery Status
🔹Final Amount, Price per Unit

✔ Data quality improvements:

Removed duplicates across all tables

Cleaned city/location inconsistenc
🔗 Data Modeling (Power BI)
Designed a Star Schema Architecture:
Fact Table: Orders
Dimension Tables: Users, Restaurants
Relationships:
Users → Orders (user_id)
Restaurants → Orders (r_id)
Applied single-direction filtering for optimized performance
📊 Key Metrics (DAX)
💰 Total Revenue
📦 Total Orders
📈 Average Order Value (AOV)
👥 Total & Active Users
⭐ Average Restaurant Rating
🏙️ Total Cities
📊 Dashboard Features
🔹 1. Executive Overview
KPI cards (Revenue, Orders, Users, Restaurants)
Revenue trend analysis
Top-performing restaurants
Geographic distribution (map)
🔹 2. Restaurant Insights
Cuisine performance analysis
Rating vs revenue comparison
Top restaurants by orders
Pricing and demand trends
🔹 3. Customer Insights
User segmentation (Age, Income, Family Type)
User growth trends
Gender distribution
Education vs income analysis
🔍 Key Insights
💡 High-income users contribute disproportionately to total revenue
🍜 Mid-range restaurants generate the highest order volume
🚚 Faster delivery times correlate with better customer engagement
🌆 Urban cities dominate both orders and revenue
