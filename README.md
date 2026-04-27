# 🛒 **Online Shopping SQL Analysis (RetailDB_1)**

---

## 📌 **Project Overview**

This project delivers a comprehensive **SQL-based data analysis** on a simulated **Online Shopping platform database**.

The primary objective is to analyze customer behavior and transactional data to understand:

- 🧑‍💻 **Customer registration patterns**
- 🛍️ **Purchasing behavior**
- 💰 **Order value trends**

The project focuses on building strong SQL fundamentals by working with **realistic relational data**, including customers, products, and orders.

---

## 👤 **Author Information**

- **Name:** Aman Singh  
- **Role:** Data Analyst  
- **Contact:** +91 8400795449  

---

## 🎯 **Key Research Questions**

This analysis addresses the following database and business-related questions:

- **Customer Insights:** Who are the customers and where do they belong?  
- **Location Analysis:** Which cities have the highest customer presence?  
- **Order Trends:** What orders were placed after a specific date (e.g., 1st August 2024)?  
- **Product Pricing:** Which products are priced above ₹5000?  
- **Customer Count:** How many total customers exist in the system?  
- **Data Modification:** How can customer details be updated (e.g., city change)?  
- **Data Deletion:** How can specific records (orders) be removed?  
- **Price Analysis:** What is the price after applying a 10% increase?  
- **Unique Values:** What are the distinct cities customers belong to?  
- **Pagination Logic:** How to fetch limited and offset-based records?  
- **Range Queries:** Which products fall within a price range (₹2000–₹6000)?  
- **Conditional Filtering:**  
  - Customers from Mumbai OR Chennai  
  - Customers NOT from Delhi  
- **Payment Analysis:** Which orders are not paid via UPI?  
- **Aggregate Metrics:**  
  - Average order amount  
  - Highest order value  
  - Lowest product price  
  - Total revenue generated  

---

## 📂 **Dataset Description**

The project uses a relational database named **RetailDB_1** consisting of three core tables:

### 🧑 Customers Table
Stores customer details:

- **customer_id**
- **name**
- **email**
- **city**
- **signup_date**

---

### 📦 Products Table
Contains product-related information:

- **product_id**
- **product_name**
- **category**
- **price**

---

### 🧾 Orders Table
Tracks all customer transactions:

- **order_id**
- **customer_id** (Foreign Key)
- **product_id** (Foreign Key)
- **order_date**
- **quantity**
- **total_amount**
- **payment_mode**

---

## ⚙️ **Database Operations Covered**

This project demonstrates practical SQL operations including:

- ✅ **SELECT queries** (basic & filtered retrieval)  
- 🔄 **UPDATE queries** (modifying records)  
- ❌ **DELETE queries** (removing records)  
- 🔍 **WHERE conditions** (filtering data)  
- 📊 **Aggregate functions** (`COUNT`, `AVG`, `MAX`, `MIN`, `SUM`)  
- 📑 **Sorting & Limiting** (`LIMIT`, `OFFSET`)  
- 🎯 **Conditional operators** (`BETWEEN`, `IN`, `NOT`, `OR`)  
- 🧠 **Data transformation** (price increase calculation)  

---

## 🛠️ **Project Workflow**

1. **Database Creation**  
2. **Table Creation (Customers, Orders, Products)**  
3. **CSV Data Import**  
4. **Data Validation & Display**  
5. **SQL Query Execution for Analysis**  

---

## 📈 **Outcome**

By completing this project, you gain:

- Strong foundation in **SQL querying**
- Practical understanding of **relational databases**
- Ability to perform **real-world data analysis tasks**
- Experience with **data cleaning, transformation, and aggregation**

---
