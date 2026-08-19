# AdventureWorks Sales Analysis Dashboard

## 📊 Project Overview

Welcome to my first portfolio project --- **AdventureWorks Sales
Analysis**.

In this project, I cleaned and prepared the AdventureWorks sales dataset
using **SQL**, performed data analysis, and created an interactive
**3-page Power BI dashboard** to understand sales performance across
customers, products, categories, cities, and months.

I also exported the Power BI dashboard as a **PDF** for easy sharing and
portfolio presentation.

------------------------------------------------------------------------

## 🎯 Project Objectives

The main objectives of this project were to:

-   Clean and prepare raw AdventureWorks data using SQL
-   Select only the columns required for analysis and visualization
-   Analyze sales performance by month, customer, product, category, and
    location
-   Identify top customers and best-selling products
-   Compare monthly sales against budget
-   Build an interactive Power BI dashboard
-   Create a clean and portfolio-ready sales analytics report

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

  -----------------------------------------------------------------------
  Tool                                Purpose
  ----------------------------------- -----------------------------------
  **SQL**                             Data cleaning, filtering, sorting,
                                      and preparation

  **Microsoft Power BI**              Data modeling, analysis,
                                      visualization, and dashboard
                                      creation

  **Excel**                           Supporting data source

  **CSV**                             Cleaned data exchange between SQL
                                      and Power BI

  **Power BI PDF Export**             Static version of the dashboard
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 🗂️ Dataset & Data Preparation

The project uses the **AdventureWorks** dataset.

The data was prepared using SQL before importing it into Power BI.

The cleaned data was exported into CSV files containing only the fields
required for the dashboard.

### Data preparation workflow

``` text
AdventureWorks Raw Data
          ↓
       SQL Queries
          ↓
Data Cleaning & Filtering
          ↓
Select Required Columns
          ↓
      Export CSVs
          ↓
 Import into Power BI
          ↓
   Data Modeling
          ↓
 Dashboard Creation
```

The Power BI model combines the cleaned CSV tables with an Excel
worksheet.

------------------------------------------------------------------------

# 📈 Dashboard Pages

## 1. Sales Overview

The **Sales Overview** dashboard provides a high-level view of business
performance.

### Key visuals

-   Sales by Product Category
-   Top 10 Customers by Sales
-   Top 10 Best-Selling Products
-   Budget vs Sales by Month
-   Sales by Customer City
-   Year and month filters
-   Customer city, product subcategory, product category, and product
    filters

### Key insights

-   **Bikes** contribute the majority of sales, accounting for
    approximately **93.7%** of the displayed category sales.
-   Accessories and Clothing contribute much smaller portions of the
    total.
-   The dashboard makes it easy to identify the highest-value customers
    and products.
-   Monthly sales can be compared directly with the budget to identify
    periods of underperformance or overperformance.
-   Sales are distributed across multiple regions, including North
    America, Europe, and Australia.

------------------------------------------------------------------------

## 2. Sales by Customer

This page focuses on customer-level sales performance.

### Key visuals

-   Sales by Customer City map
-   Top 10 Customers by Sales
-   Monthly customer sales matrix
-   Total sales by customer

### Example top customers

  Customer             Sales
  --------------- ----------
  Jordan Turner     \$11,484
  Maurice Shan      \$10,861
  Janet Munoz       \$10,418
  Nichole Nara       \$9,717
  Margaret He        \$9,691

The customer matrix also allows monthly sales patterns to be compared
across customers.

------------------------------------------------------------------------

## 3. Sales by Product

This page focuses on product-level performance.

### Key visuals

-   Sales by Customer City
-   Top 10 Best-Selling Products
-   Monthly product sales matrix
-   Total sales by product

### Example top products

  Product                         Sales
  ------------------------- -----------
  Mountain-200 Black, 42      \$970,781
  Mountain-200 Silver, 38     \$967,436
  Mountain-200 Black, 38      \$947,831
  Mountain-200 Black, 46      \$947,831
  Mountain-200 Silver, 46     \$923,356

The product matrix uses conditional formatting to make high and low
sales values easier to identify.

------------------------------------------------------------------------

# 🔍 Key Business Insights

Based on the dashboard:

1.  **Bikes dominate the sales mix**, representing the largest share of
    category sales.
2.  **Mountain-200 products are among the strongest-performing
    products**, with several variants exceeding \$900K in sales.
3.  **Top customers contribute significant individual sales values**,
    with the leading customer generating more than \$11K in the
    displayed customer analysis.
4.  **Monthly sales fluctuate throughout the year**, making
    budget-vs-sales analysis useful for identifying performance gaps.
5.  Sales are geographically distributed across **North America, Europe,
    and Australia**.
6.  Customer and product monthly matrices make it easier to identify
    changes in purchasing behavior and sales concentration.

> Note: The insights above are based on the data represented in the
> dashboard and may change when filters such as year, month, city,
> category, subcategory, or product are applied.

------------------------------------------------------------------------

# 📊 Power BI Features Used

The dashboard includes:

-   Interactive slicers
-   KPI-style summaries
-   Donut chart
-   Horizontal bar charts
-   Line chart
-   Map visualization
-   Matrix tables
-   Conditional formatting
-   Cross-filtering
-   Year and month selection
-   Product and customer filtering
-   Data modeling and table relationships

------------------------------------------------------------------------

# 📁 Project Structure

Recommended GitHub repository structure:

``` text
AdventureWorks-Sales-Analysis/
│
├── README.md
│
├── SQL/
│   ├── customer_cleaning.sql
│   ├── product_cleaning.sql
│   ├── sales_cleaning.sql
│   └── ...
│
├── Data/
│   ├── customer.csv
│   ├── product.csv
│   ├── sales.csv
│   ├── ...
│   └── supporting_data.xlsx
│
├── PowerBI/
│   └── AdventureWorks_Sales_Dashboard.pbix
│
├── PDF/
│   └── AdventureWorks_Sales_Dashboard.pdf
│
└── Images/
    ├── sales-overview.png
    ├── sales-by-customer.png
    └── sales-by-product.png
```

------------------------------------------------------------------------

# 🖼️ Dashboard Preview

### Sales Overview

![Sales Overview](Images/sales by customer.jpeg)

### Sales by Customer

![Sales by Customer](Images/sales-by-customer.png)

### Sales by Product

![Sales by Product](Images/sales-by-product.png)

------------------------------------------------------------------------

# 🚀 What I Learned

Through this project, I gained practical experience in:

-   SQL data cleaning
-   Data extraction and transformation
-   Selecting analysis-ready columns
-   CSV and Excel data handling
-   Power BI data modeling
-   Creating relationships between tables
-   Building interactive dashboards
-   Creating business-focused visualizations
-   Using slicers and filters
-   Creating matrix reports
-   Presenting business insights through data visualization

------------------------------------------------------------------------

# 💡 Future Improvements

Possible improvements for future versions include:

-   Adding profit and profit-margin analysis
-   Adding year-over-year growth metrics
-   Adding additional KPIs such as average order value
-   Creating more detailed regional analysis
-   Adding customer segmentation
-   Adding automated data refresh
-   Publishing the dashboard to Power BI Service

------------------------------------------------------------------------

# 👩‍💻 About the Project

This project was created as part of my **Data Analytics portfolio** to
demonstrate practical skills in **SQL, Excel, Power BI, data cleaning,
data analysis, and dashboard development**.

**Role:** Data Analyst / BI Developer\
**Tools:** SQL • Excel • Power BI\
**Dataset:** AdventureWorks
