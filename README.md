# Snowflake_miniproject-1
# ❄️ Snowflake Mini Project – Sales Analytics

## 📌 Project Overview
This is a beginner-friendly Snowflake mini project created to understand
how data engineers work with Snowflake for data loading, transformation,
and analytics.

The project demonstrates database setup, data loading using stages and
COPY INTO, and basic data modeling using fact and dimension tables.

---

## 🛠️ Tools & Technologies
- Snowflake (Cloud Data Warehouse)
- SQL
- CSV File (Sales Data)

---

## 🗂️ Project Architecture
CSV File  
→ Snowflake Internal Stage  
→ Raw Table  
→ Dimension Tables  
→ Fact Table  
→ Analytical Queries

---

## 📊 Dataset Description
The dataset contains sales transaction data with the following fields:
- Order ID
- Order Date
- Customer Name
- Product
- Quantity
- Price

---

## 🧱 Project Steps

### 1️⃣ Environment Setup
- Created Database
- Created Schema
- Created Warehouse

### 2️⃣ Data Loading
- Created internal stage
- Uploaded CSV file
- Loaded data using COPY INTO command

### 3️⃣ Data Modeling
- Created Raw Sales Table
- Created Dimension Tables:
  - dim_product
  - dim_date
- Created Fact Table:
  - fact_sales

### 4️⃣ Data Transformation
- Joined raw data with dimensions
- Calculated revenue
- Created analytical views

### 5️⃣ Analytics
- Total Revenue
- Daily Sales
- Top Selling Products

---

## 🧠 Key Learnings
- Snowflake architecture (Database, Schema, Warehouse)
- Data loading using internal stages and COPY INTO
- Star schema (Fact & Dimension tables)
- Writing analytical SQL queries

---

## 🎤 Interview Explanation
"I built a Snowflake sales analytics project where I created a database,
schema, and warehouse. I loaded CSV data using internal stages and COPY INTO,
designed fact and dimension tables using a star schema, and wrote SQL queries
to generate business insights."

---

## 🚀 Future Enhancements
- Load data from AWS S3
- Implement Slowly Changing Dimensions (SCD)
- Add more business metrics

