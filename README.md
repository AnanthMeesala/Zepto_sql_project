# Zepto SQL Data Analysis Project

This project focuses on analyzing FMCG/grocery inventory data from Zepto using MySQL.  
The goal of the project is to uncover trends in pricing, discounts, inventory, and category-wise revenue to support business decision-making.

The analysis includes data exploration, data cleaning, analytical SQL queries, business insights, and recommendations based on real-world retail scenarios.

---

## 📂 Dataset Overview

Each row in the dataset represents a product SKU with retail attributes.

| Column Name | Description |
|------------|-------------|
| sku_id | Unique identifier |
| category | Product category |
| name | Product name |
| mrp | Maximum Retail Price |
| discountpercent | Discount percentage |
| discountedsellingprice | Final selling price |
| availablequantity | Inventory count |
| weightinGms | Weight of product |
| outofstock | TRUE/FALSE status |
| quantity | Customer ordered quantity |

---

## 🛠 Tools & Skills Used
- **MySQL**
- **Data Exploration**
- **Data Cleaning using SQL**
- **Aggregations (SUM, AVG, COUNT)**
- **GROUP BY, HAVING, ORDER BY**
- **CASE Statements**
- **Business-focused analytical problem solving**

---

## 🔍 Project Workflow

### 1️⃣ Data Exploration
- Row count check  
- Sample data preview  
- NULL value identification  
- Unique category listing  
- Duplicate product detection  
- Stock availability analysis  

### 2️⃣ Data Cleaning
- Removed SKUs with **MRP = 0**
- Converted **Paise → Rupees**
- Standardized numeric fields for accurate analysis

### 3️⃣ Business Analytics Using SQL
The project answers multiple business questions such as:
| Business Question | Purpose |
|-------------------|---------|
| Top discounted products | Identify best value deals |
| High-MRP products out of stock | Detect revenue leakages |
| Estimated revenue by category | Identify profitable product segments |
| Premium products | Segmentation based on price & discount |
| Highest discount categories | Impact of promotions |
| Best price per gram value | Customer value proposition |
| Weight-based classification | Logistics & packaging efficiency |
| Total inventory weight per category | Stock capacity & planning |

---
