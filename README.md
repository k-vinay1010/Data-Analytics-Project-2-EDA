# 📊 Data Analytics Project 2 – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of the **DecodeLabs Data Analytics Industrial Training Program**.

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on an e-commerce order dataset to uncover patterns, trends, distributions, relationships, and potential outliers.

The analysis was performed using **Microsoft Excel**, with descriptive statistics, product-level analysis, time-based trends, outlier detection, correlation analysis, order-status analysis, and referral-source analysis.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Understand the structure and distribution of the dataset
- Calculate descriptive statistics such as:
  - Mean
  - Median
  - Minimum
  - Maximum
  - Count
- Analyze product-level sales performance
- Identify trends over time
- Detect potential outliers using the IQR method
- Analyze correlations between numerical variables
- Analyze order status and referral sources
- Extract meaningful business insights from the data

---

## 📂 Dataset

The dataset contains **1,200 e-commerce order records**.

### Key variables include:

- `OrderID`
- `Date`
- `Product`
- `Quantity`
- `UnitPrice`
- `TotalPrice`
- `ItemsInCart`
- `OrderStatus`
- `ReferralSource`

The data covers orders from **2023 through June 2025**.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- Data Cleaning
- Descriptive Statistics
- Exploratory Data Analysis
- Pivot Tables / Aggregation
- IQR-based Outlier Analysis
- Correlation Analysis
- Data Visualization

---

## 📊 Analysis Performed

### 1. Descriptive Statistics

Calculated descriptive statistics for important numerical variables including:

| Variable | Mean | Median |
|---|---:|---:|
| Quantity | 2.95 | 3 |
| Unit Price | ₹356.41 | ₹364.21 |
| Items in Cart | 5.48 | 5 |
| Total Price | ₹1,053.97 | ₹823.62 |

These statistics provide an overview of the central tendency and distribution of the numerical variables.

---

### 2. Product Analysis

Total sales were analyzed across different products.

| Product | Total Sales |
|---|---:|
| Chair | ₹195,620.11 |
| Printer | ₹195,612.61 |
| Laptop | ₹192,126.56 |
| Tablet | ₹186,568.95 |
| Monitor | ₹175,651.41 |
| Desk | ₹167,459.93 |
| Phone | ₹151,722.39 |

The analysis shows differences in sales contribution across the product categories.

---

### 3. Time Trend Analysis

Order and sales data were analyzed over time to identify changes and patterns across the available period.

The analysis helps understand how sales activity changes over the dataset's timeline and provides a foundation for further time-series analysis.

---

### 4. Outlier Analysis

The **Interquartile Range (IQR)** method was used to identify potential outliers in `TotalPrice`.

- Q1: **₹410.52**
- Q3: **₹1,578.48**
- IQR: **₹1,167.96**
- Upper boundary: **₹3,330.42**
- Values above the upper boundary: **8**

The identified high-value observations were reviewed against the relationship between quantity and unit price and were retained in the analysis.

---

### 5. Correlation Analysis

Correlation analysis was performed to understand relationships between numerical variables and `TotalPrice`.

| Variable | Correlation with TotalPrice |
|---|---:|
| Quantity | ~0.615 |
| Unit Price | ~0.717 |
| Items in Cart | ~0.393 |

The results indicate positive relationships between these variables and total order value.

**Important:** Correlation indicates association and does not by itself establish causation.

---

### 6. Order Status Analysis

The dataset was also analyzed based on order status.

| Order Status | Orders | Total Sales |
|---|---:|---:|
| Cancelled | 250 | ₹276,396.21 |
| Returned | 247 | ₹243,277.70 |
| Pending | 237 | ₹256,328.15 |
| Shipped | 235 | ₹246,159.58 |
| Delivered | 231 | ₹242,600.32 |

This analysis provides visibility into the distribution of orders across different fulfillment statuses.

---

### 7. Referral Source Analysis

Orders were grouped by referral source to understand the contribution of different acquisition channels.

| Referral Source | Orders | Total Sales |
|---|---:|---:|
| Instagram | 259 | ₹275,285.45 |
| Email | 250 | ₹261,808.55 |
| Google | 241 | ₹250,441.48 |
| Facebook | 228 | ₹250,410.90 |
| Referral | 222 | ₹226,815.58 |

This analysis provides a view of order activity and sales associated with each referral source.

---

## 💡 Key Insights

The EDA produced several useful observations:

- The dataset contains **1,200 order records** covering multiple products and order statuses.
- **Chair and Printer** recorded the highest total sales among the listed products, with very similar sales values.
- **Unit Price** has the strongest positive correlation with `TotalPrice` among the analyzed numerical variables.
- `Quantity` also shows a moderate positive relationship with `TotalPrice`.
- **8 high-value TotalPrice observations** were identified using the IQR method.
- **Instagram** recorded the highest number of orders among the referral sources in this dataset.
- Order-status analysis shows a substantial number of records across cancelled, returned, pending, shipped, and delivered categories.
- The analysis demonstrates how descriptive statistics, trends, outlier analysis, and correlation can be combined to understand an e-commerce dataset.

---

## 📁 Project Files

### `Data_Analytics_Project_2_EDA.xlsx`

The Excel workbook contains the complete analysis with the following sheets:

- `Cleaned_Data`
- `EDA_Summary`
- `Descriptive_Statistics`
- `Product_Analysis`
- `Time_Trend`
- `Outlier_Analysis`
- `Correlation`
- `Insights`
- `Status_Analysis`
- `Referral_Analysis`

---

## 📈 EDA Workflow

```text
Raw Dataset
     ↓
Data Preparation
     ↓
Descriptive Statistics
     ↓
Product Analysis
     ↓
Time Trend Analysis
     ↓
Outlier Detection
     ↓
Correlation Analysis
     ↓
Status & Referral Analysis
     ↓
Business Insights
```

---

## 🎓 Skills Demonstrated

Through this project, I practiced:

- Data Analysis
- Exploratory Data Analysis (EDA)
- Microsoft Excel
- Descriptive Statistics
- Data Aggregation
- Outlier Detection
- IQR Method
- Correlation Analysis
- Trend Analysis
- Business Insight Generation
- Data Interpretation

---

## 🚀 Learning Outcome

This project helped me understand how to move beyond simply cleaning data and start **exploring data to identify meaningful patterns and relationships**.

It also strengthened my ability to communicate analytical findings in a structured and business-oriented manner.

---

## 👨‍💻 Author

**K. Vinay**

BBA Business Analytics  
Osmania University, Hyderabad

### 🔗 Connect with me

- LinkedIn: [K. Vinay](https://www.linkedin.com/in/k-vinay-b1b789424/)

---

## 📌 Project Series

**Project 1:** Data Cleaning and Preparation  
**Project 2:** Exploratory Data Analysis (EDA)

More data analytics projects will be added as I continue building my Data Analyst portfolio.
