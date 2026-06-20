# 🛒 Zepto Product Data Analysis using SQL

## 📌 Project Overview
This project focuses on analyzing Zepto's product dataset using SQL to uncover valuable business insights. The analysis includes data cleaning, exploratory data analysis (EDA), inventory analysis, pricing insights, discount evaluation, and revenue estimation.

The objective is to demonstrate real-world SQL skills used by Data Analysts for data cleaning, querying, aggregation, and business reporting.

---

## 🎯 Project Goals

- Clean and prepare raw product data
- Identify data quality issues
- Analyze discounts and pricing strategies
- Evaluate inventory availability
- Estimate category-wise revenue
- Discover high-value products
- Generate business insights using SQL

---

## 🛠️ Tools & Technologies

- PostgreSQL
- SQL
- GitHub

---

## 📂 Dataset Information

The dataset contains product-related information from Zepto, including:

- Product Name
- Category
- MRP
- Discount Percentage
- Available Quantity
- Discounted Selling Price
- Product Weight
- Stock Availability

---

## 🧹 Data Cleaning Performed

### 1. Null Value Check
Validated all columns for missing values.

### 2. Duplicate Product Analysis
Identified products appearing multiple times with different SKU IDs.

### 3. Invalid Data Removal
Removed records where:

- MRP = 0
- Discounted Selling Price = 0

### 4. Data Standardization
Converted prices from paise to rupees by dividing values by 100.

---

## 📊 Exploratory Data Analysis (EDA)

### Product & Inventory Analysis
- Total number of products
- Distinct product categories
- In-stock vs Out-of-stock products
- Duplicate product identification

### Pricing & Discount Analysis
- Top 10 products with highest discounts
- High MRP products currently out of stock
- Products priced above ₹500 with discounts below 10%
- Categories with highest average discounts

### Revenue Analysis
- Estimated revenue by category

### Weight-Based Analysis
- Price per gram calculation
- Product segmentation:
  - Low Weight
  - Medium Weight
  - Bulk Weight
- Total inventory weight per category

---

## 🔍 Key SQL Business Questions Solved

### Q1. Top 10 Best Value Products
Products offering the highest discount percentages.

### Q2. High MRP Products Out of Stock
Premium products unavailable for purchase.

### Q3. Estimated Revenue by Category
Potential revenue generated from available inventory.

### Q4. Premium Products with Low Discounts
Products with MRP > ₹500 and discount < 10%.

### Q5. Categories with Highest Average Discounts
Top categories providing maximum savings to customers.

### Q6. Best Value by Price per Gram
Products delivering maximum quantity for the lowest cost.

### Q7. Product Weight Segmentation
Classification into Low, Medium, and Bulk categories.

### Q8. Total Inventory Weight per Category
Analysis of inventory volume across categories.

---

## 📈 Business Insights

- Identified highly discounted products that attract customers.
- Estimated revenue potential across product categories.
- Discovered premium products facing stock shortages.
- Compared category-level discount strategies.
- Evaluated product value using price-per-gram metrics.
- Assessed inventory distribution by category.

---

## 🚀 Skills Demonstrated

- SQL Query Writing
- Data Cleaning
- Data Validation
- Aggregate Functions
- CASE Statements
- Sorting & Filtering
- Business Analysis
- Inventory Analytics
- Revenue Estimation
- Exploratory Data Analysis (EDA)

---

## 📁 Repository Structure

├── dataset/
│   └── zepto_dataset.csv
│
├── sql/
│   └── zepto_analysis.sql
│
└── README.md

---

## 👨‍💻 Author

Anurag Patil

Aspiring Data Analyst skilled in:

- SQL
- PostgreSQL
- Python (Pandas, NumPy, Matplotlib)
- Power BI
- Data Analysis
- Data Visualization

---

⭐ If you found this project useful, consider giving it a star.
