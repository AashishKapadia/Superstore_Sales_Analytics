# Superstore Sales Analytics

## 📊 Project Overview

**Superstore Sales Analytics** is an end-to-end **Business Intelligence
and Data Analytics project** built using the Superstore retail dataset
and **Microsoft Power BI**.

The project transforms transactional sales data into an interactive
dashboard for analyzing:

-   Sales performance
-   Profitability
-   Customer performance
-   Product and category performance
-   Regional trends
-   Time-based sales trends
-   Order and transaction analysis

The goal is to turn raw retail data into a clear, decision-oriented
dashboard that helps stakeholders identify growth opportunities,
understand profitable areas, and detect areas requiring attention.

## 🎯 Project Objectives

1.  Analyze overall sales and profitability performance.
2.  Identify strong and weak-performing products and categories.
3.  Understand customer and regional contribution to sales.
4.  Analyze sales trends across time.
5.  Compare sales and profit across business dimensions.
6.  Build an interactive Power BI dashboard.
7.  Convert raw transactional data into actionable business insights.

## 🛠️ Tools & Technologies

  -----------------------------------------------------------------------
  Tool                                Purpose
  ----------------------------------- -----------------------------------
  **Microsoft Power BI**              Data modeling, DAX, dashboard
                                      development and visualization

  **CSV**                             Source Superstore sales data

  **DAX**                             KPI calculations and analytical
                                      measures

  **Power Query**                     Data cleaning and transformation

  **Data Visualization**              Interactive charts, KPIs and
                                      business storytelling
  -----------------------------------------------------------------------

## 📁 Repository Contents

-   `Sales.pbix` --- Power BI dashboard and data model
-   `Sample - Superstore.csv` --- Superstore source dataset
-   `Superstore_Sales_Analytics_Portfolio_Report.pdf` --- Detailed
    project portfolio report
-   `LICENSE` --- MIT License

## 🔄 Project Workflow

``` text
Raw Superstore Data
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
DAX Measures / KPIs
        ↓
Exploratory Analysis
        ↓
Interactive Power BI Dashboard
        ↓
Business Insights & Recommendations
```

## 📌 Dashboard Analysis

### Sales Performance

The dashboard provides an overall view of sales performance and allows
users to investigate revenue across different periods and business
dimensions.

### Profitability Analysis

Profit is analyzed alongside sales to identify high-sales/low-profit
areas, profitable categories, and areas where pricing or discount
strategies may require attention.

### Product & Category Analysis

Product and category views help identify strong and weak contributors to
overall business performance and support product portfolio decisions.

### Customer Analysis

Customer analysis helps understand customer contribution, identify
high-value customers and support targeted strategies.

### Regional Analysis

Regional views compare sales and profitability across geographic areas
and help identify strong and weak markets.

### Time-Series Analysis

Time-based views help identify trends, seasonal patterns and changes in
business performance across periods.

## 📈 Key Business Questions

-   What is the overall sales performance?
-   Which categories generate the most sales?
-   Which products and categories are most profitable?
-   Which customers contribute the most value?
-   Which regions perform best?
-   How does sales performance change over time?
-   Where are potential profitability issues?
-   Which areas should management prioritize?

## 💡 Business Value

The dashboard demonstrates how retail organizations can use Power BI to
move from raw transactional data to business-oriented insights.

It can support:

-   Sales performance monitoring
-   Profitability improvement
-   Product and category decisions
-   Regional strategy
-   Customer analysis
-   Trend monitoring
-   Data-driven decision making

> **Note:** Exact KPI values and category-level figures should be read
> from the current Power BI workbook/dashboard rather than being
> hard-coded into this README.

## 🧮 KPI & DAX Approach

Example measures that can be adapted to the final Power BI model:

``` dax
Total Sales = SUM('Superstore'[Sales])

Total Profit = SUM('Superstore'[Profit])

Total Orders = DISTINCTCOUNT('Superstore'[Order ID])

Total Customers = DISTINCTCOUNT('Superstore'[Customer ID])

Profit Margin = DIVIDE([Total Profit], [Total Sales])
```

> Adjust table and column names to match the final model.

## 📊 Dashboard Design

The dashboard uses:

-   KPI cards
-   Trend charts
-   Product and category analysis
-   Regional analysis
-   Interactive filters
-   Comparative visuals
-   Business-focused storytelling

The objective is to move from a high-level executive view to detailed
analysis without working directly with raw data.

## 🧠 Skills Demonstrated

-   Power BI
-   Power Query
-   DAX
-   Data Cleaning
-   Data Transformation
-   Data Modeling
-   KPI Development
-   Sales Analytics
-   Profitability Analysis
-   Customer Analysis
-   Product Analysis
-   Regional Analysis
-   Time-Series Analysis
-   Data Visualization
-   Business Intelligence
-   Data Storytelling

## 📂 Dataset

The repository includes `Sample - Superstore.csv`, which is used as the
source for the Power BI analysis.

## ▶️ How to Use

1.  Clone or download this repository.
2.  Open `Sales.pbix` using Microsoft Power BI Desktop.
3.  If required, update the source path for `Sample - Superstore.csv`.
4.  Refresh the dataset.
5.  Explore the dashboard using its filters and visuals.
6.  Review `Superstore_Sales_Analytics_Portfolio_Report.pdf` for the
    detailed project documentation.

## 📄 Portfolio Report

A detailed portfolio report is included:

`Superstore_Sales_Analytics_Portfolio_Report.pdf`

## 🚀 Future Improvements

-   Sales forecasting
-   Year-over-year growth KPIs
-   Customer segmentation
-   RFM analysis
-   Product-level profitability analysis
-   Drill-through pages
-   Advanced DAX measures
-   Predictive analytics
-   Dynamic KPI selection
-   Automated data refresh

## 👨‍💻 Author

**Aashish Kapadia**

Data Analytics \| Business Intelligence \| Power BI

## 📜 License

This project is licensed under the **MIT License**.

Copyright © 2026 Aashish Kapadia.
