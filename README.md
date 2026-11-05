# E-Commerce Customer Behavior & Sales Analysis

## Project Overview

This project analyzes an e-commerce customer behavior and sales dataset containing **5,000 transaction records** covering the period from January 2023 to March 2024.

The objective is to evaluate sales performance, understand customer purchasing behavior, identify revenue patterns, and extract actionable business insights using Microsoft Excel.

The project includes data quality assessment, exploratory data analysis, KPI calculations, PivotTables, and an interactive Excel dashboard.

## Business Objectives

- Evaluate overall sales performance using key business metrics.
- Identify the highest-revenue product categories and cities.
- Analyze customer preferences across payment methods and device types.
- Examine customer satisfaction through customer ratings.
- Compare new and returning customers.
- Evaluate delivery performance across different cities.
- Present key findings through an interactive dashboard.

## Dataset Description

- **Records:** 5,000 transactions
- **Columns:** 18
- **Analysis Period:** January 2023 – March 2024
- **Data Type:** E-commerce transaction and customer behavior data

The dataset includes information about:

- Orders and customers
- Product categories and sales amounts
- Dates and payment methods
- Customer demographics
- Device types and shopping behavior
- Delivery times and customer ratings

## Tools & Technologies

- **Microsoft Excel**
- Excel Tables
- PivotTables and PivotCharts
- Excel Formulas
- Data Cleaning and Validation
- Data Visualization
- Interactive Dashboard

## Methodology

The project followed a structured analytical workflow:

1. **Data Inspection:** Reviewed dataset structure, columns, records, and data types.
2. **Data Preparation:** Created a working dataset while preserving the original raw data.
3. **Data Quality Assessment:** Checked missing values, duplicate Order IDs, invalid values, logical consistency, and returning-customer values.
4. **Exploratory Data Analysis:** Examined sales and customer behavior across multiple business dimensions.
5. **KPI Calculation:** Calculated key performance indicators.
6. **Data Visualization:** Created PivotCharts and an interactive dashboard.
7. **Reporting:** Documented findings and recommendations in a structured report.

## Data Quality Assessment

Six data quality checks were performed:

| Quality Check | Result |
|---|---|
| Missing Values | 0 – Pass |
| Duplicate Order IDs | 0 – Pass |
| Data Types | Pass – Manual Review |
| Invalid Values | 0 – Pass |
| Logical Consistency | 0 – Pass |
| Returning Customer Values | Pass – 0 Invalid |

**Result: 6 of 6 checks passed.**

Note: Duplicate checks focused on Order_ID values. Data types were reviewed manually.

## Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Revenue | 4,915,544.57 |
| Total Orders | 5,000 |
| Quantity Sold | 11,100 |
| Total Discounts | 124,264.02 |
| Average Order Value | 983.11 |

## Key Business Findings

### 1. Sales Performance by Product Category

- Electronics generated the highest revenue: **2,328,806.81**.
- Home & Garden ranked second with **908,348.86**.
- Sports recorded the highest quantity sold with **1,519 units**.

### 2. Sales Performance by City

- Istanbul generated the highest revenue: **1,334,122.56**.
- Ankara ranked second with **657,535.82**.
- Eskisehir recorded the lowest revenue: **178,978.43**.

### 3. Payment Method Analysis

- Credit Card was the most frequently used payment method, with **2,012 orders**.
- Credit Card and Debit Card together accounted for approximately **65.54% of all orders**.

### 4. Device Type Analysis

- Mobile devices generated **2,810,468.64** in revenue.
- Mobile accounted for approximately **57.17% of total revenue** and **55.9% of all orders**.

### 5. Customer Satisfaction

- **71.56%** of orders received four- or five-star ratings.
- Five-star ratings represented the largest individual rating category.

### 6. New vs. Returning Customers

- Returning customers accounted for **59.8% of all orders**.
- They generated **2,948,020.84** in revenue.
- Their contribution to total revenue was higher than that of new customers.

### 7. Delivery Performance

- Average delivery time was **6.50 days**.
- Konya recorded the shortest average delivery time at **5.95 days**.
- Istanbul recorded the longest average delivery time at **6.67 days**.

### 8. Monthly Revenue Analysis

- January 2024 recorded the highest monthly revenue at **396,874.92**.
- August 2023 followed with **391,505.89**.
- April 2023 recorded the lowest monthly revenue at **257,332.58**.

### 9. Customer Demographics

- Customers aged 35–44 generated the highest revenue: **1,483,006.07**.
- Female customers generated **2,474,009.26** in revenue.
- Male customers generated **2,381,028.70** in revenue.

## Dashboard Preview

The interactive Excel dashboard presents the main KPIs and visualizations covering:

- Monthly Revenue Trend
- Revenue by Product Category
- Quantity Sold by Product Category
- Revenue by City
- Revenue by Payment Method
- Revenue by Device Type
- Customer Rating Distribution
- New vs. Returning Customers

Dashboard screenshots are available in the `Dashboard/` folder.

## Recommendations

Based on the analysis, the following recommendations were identified:

- Strengthen performance in the Electronics category.
- Investigate sales patterns in high-revenue cities.
- Optimize the mobile shopping experience.
- Monitor customer satisfaction and feedback.
- Encourage customer retention through loyalty initiatives.
- Monitor delivery performance and identify opportunities for improvement.

## Project Structure

```text
Ecommerce-Customer-Behavior-Analysis/
│
├── README.md
├── Ecommerce_Customer_Behavior_Analysis.xlsx
│
├── Report/
│   ├── Ecommerce_Customer_Behavior_Analysis_Report.pdf
│   └── Ecommerce_Customer_Behavior_Analysis_Report.docx
│
├── Dashboard/
│   ├── Dashboard_Page_1.png
│   └── Dashboard_Page_2.png
│
└── Data/
    └── Ecommerce_Customer_Behavior.csv
```

## Conclusion

This project demonstrates how Microsoft Excel can be used to transform raw e-commerce transaction data into structured analysis, meaningful business insights, and interactive visualizations.

It showcases practical data analytics skills in data preparation, validation, exploratory analysis, KPI development, PivotTables, dashboard creation, and business reporting.

---

**Author:** Khalil Azennoud  
**Project Type:** Data Analytics Portfolio Project  
**Tools:** Microsoft Excel
