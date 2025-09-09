# Sales Data Analysis - SQL Project

## 📊 Project Overview

A comprehensive data analysis project that explores a sales database to derive actionable business intelligence. This repository demonstrates the full data analysis workflow, from cleaning raw data in Excel to performing SQL queries and documenting key insights in MySQL.


## 🛠️ Technologies Used

- **Data Cleaning & Preparation:** Microsoft Excel
- **Database Management System:** MySQL
- **Data Analysis:** SQL (Structured Query Language)
- **Version Control:** Git & GitHub


## 📁 Repository Structure

```
sales-data-analysis-with-sql/
├── data/
│   ├── sales_data_raw.csv          # Original, uncleaned dataset
│   └── sales_data_processed.csv    # Cleaned, analysis-ready dataset
│
├── scripts/
│   └── sales_analysis.sql          # Main SQL analysis script
│
├── results/                        # Query results (CSV exports)
│   ├── Q2_total_orders.csv
│   ├── Q3_date_range.csv
│   └── ...                         # Other result files
│
└── README.md                       # Project documentation (this file)
```

## 🔍 Key Insights & Analysis

The SQL analysis script (`sales_analysis.sql`) contains 14 queries that answer important business questions. Here is a summary of the key findings:

### 📈 Orders Overview
- **Total Orders:** 2,823
- **Date Range:** Orders span from January 6, 2003, to May 31, 2005.
- **Order Status:** The vast majority of orders (2,617) were successfully `Shipped`.

### 💰 Financial Performance
- **Total Revenue:** $10,032,628.85
- **Annual Sales Growth:** 
  - 2003: $3,516,979.54
  - 2004: $4,724,162.60 (+34% growth)
  - 2005: $1,791,486.71 (partial year)
- **Average Order Value (AOV):** $3,553.89
- **Best Quarter:** Q4 generated the highest revenue ($3,874,780.01), likely due to holiday sales.

### 🏆 Top Performers
- **Best Product Line:** `Classic Cars` generated the highest revenue ($3,919,615.66), accounting for 39% of total sales.
- **Top Selling Product:** `S18_3232` (Classic Cars) generated $288,245.42 in revenue.
- **Most Valuable Customer:** `Euro Shopping Channel` was the top customer, spending $912,294.11.

### 🌍 Geographical Analysis
- **Top Market:** The USA is the leading market, generating over $3.6 million in sales, which is more than double the next highest country.
- **European Presence:** Spain, France, and the UK are strong secondary markets, demonstrating a successful international footprint.

### 📦 Sales Operations
- **Deal Size Distribution:** 
  - Medium: 1,384 orders
  - Small: 1,282 orders
  - Large: 157 orders
- **Product Demand:** `Trucks and Buses` have the highest average quantity ordered per transaction (35.80 units), indicating strong bulk purchase behavior.

## 🚀 How to Use This Repository

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/aabdl67/sales-data-analysis-with-sql.git
    ```

2.  **Explore the Data:**
    - View the raw data in `/data/sales_data_raw.csv` to understand the initial data quality challenges.
    - View the cleaned data in `/data/sales_data_processed.csv` used for analysis.

3.  **Run the Analysis:**
    - Execute the queries in `/scripts/sales_analysis.sql` in your MySQL database to reproduce the results.

4.  **Review the Findings:**
    - The CSV files in the `/results` folder contain the output of each query for quick reference.

## 📋 Conclusion

This analysis provides a solid foundation for understanding sales performance, customer behavior, and product trends.
The insights can guide strategic decisions related to inventory planning, marketing focus, and regional sales strategies.


**Skills Demonstrated:** Data Cleaning, Data Wrangling, SQL Querying, Data Analysis, Business Intelligence, and Documentation.
