# Mini-Project
# 🍽️ Zomato Analytics: End-to-End Data Analysis Project

## 🚀 Project Overview

This project presents a comprehensive analysis of Zomato data to uncover insights into **customer behavior, restaurant performance, and revenue trends**.
It combines **data preprocessing in Excel** with **interactive dashboards in Power BI** to enable data-driven decision-making.

---

## 🎯 Business Objectives

* Analyze customer demographics and spending patterns
* Evaluate restaurant performance and pricing strategies
* Identify order trends and key revenue drivers

---

## 🧩 Dataset Description

The analysis is based on three core datasets:

* 👤 **Users** – Customer demographics, income, occupation, and segmentation
* 🍽️ **Restaurants** – Cuisine, ratings, pricing, and delivery details
* 🧾 **Orders** – Transaction data including revenue, quantity, payment, and delivery

---

## 🛠️ Tools & Technologies

* **Microsoft Excel** – Data cleaning and preprocessing
* **Power BI** – Data modeling, DAX, and dashboard visualization

---

## 🔧 Data Preparation (Excel)

### ✔ Handling Missing Values

* Applied **median imputation** for numerical fields
* Used **mode imputation** for categorical fields
* Performed **category-based imputation** (e.g., income based on occupation)

### ✔ Data Standardization

* Normalized inconsistent values (e.g., *Active*, *Delivered*)
* Standardized date formats
* Cleaned and corrected categorical entries

### ✔ Feature Engineering

Created derived columns to enhance analysis:

* Age Group, Income Group, Family Type
* Rating Level, Delivery Status
* Final Amount, Price per Unit

### ✔ Data Quality Improvements

* Removed duplicate records across all tables
* Resolved city and location inconsistencies

---

## 🔗 Data Modeling (Power BI)

* Implemented a **Star Schema Architecture**:

  * **Fact Table**: Orders
  * **Dimension Tables**: Users, Restaurants

* Established relationships:

  * Users → Orders *(user_id)*
  * Restaurants → Orders *(r_id)*

* Applied **single-direction filtering** for optimized performance and accurate results

---

## 📊 Key Metrics (DAX)

* 💰 Total Revenue
* 📦 Total Orders
* 📈 Average Order Value (AOV)
* 👥 Total & Active Users
* ⭐ Average Restaurant Rating
* 🏙️ Total Cities

---

## 📊 Dashboard Features

### 🔹 1. Executive Overview

* KPI cards: Revenue, Orders, Users, Restaurants
* Revenue trend analysis
* Top-performing restaurants
* Geographic distribution (map)

### 🔹 2. Restaurant Insights

* Cuisine performance analysis
* Rating vs revenue comparison
* Top restaurants by orders
* Pricing and demand trends

### 🔹 3. Customer Insights

* User segmentation (Age, Income, Family Type)
* User growth trends
* Gender distribution
* Education vs income analysis

---

## 🔍 Key Insights

* 💡 High-income users contribute significantly to total revenue
* 🍜 Mid-range restaurants generate the highest order volume
* 🚚 Faster delivery times improve customer engagement
* 🌆 Urban cities dominate both orders and revenue

---

 
