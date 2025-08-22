# Blinkit Data Analysis Project

## Overview

This project analyzes Blinkit’s grocery sales data using **SQL, Excel, and Power BI**. The goal was to clean and transform raw data, generate insights on sales performance, and build an interactive dashboard for visualization.

## Tools & Technologies

* **SQL (SSMS)**: Data cleaning, transformation, and KPI calculations
* **Excel**: Data preprocessing and validation
* **Power BI**: Dashboard creation and visualization

## Dataset

The dataset contains grocery sales records, including fields such as:

* Item Type
* Item Fat Content
* Outlet Size
* Outlet Location Type
* Outlet Establishment Year
* Sales and Ratings

## SQL Data Analysis

Key SQL tasks performed (see `BLINKIT_DATA_ANALYSIS_SQL_QUERIES.pdf` for full queries):

1. **Data Cleaning**

   * Standardized values in `Item_Fat_Content` (e.g., mapping `LF` and `low fat` to `Low Fat`).
     
2. **KPI Calculations**

   * Total Sales
   * Average Sales
   * Number of Items
   * Average Rating
    
3. **Exploratory Queries**

   * Sales by Item Type
   * Sales by Fat Content and Outlet Location
   * Sales distribution by Outlet Size and Outlet Type
   * Yearly sales trend by Outlet Establishment

## Power BI Dashboard

The Power BI dashboard provides interactive insights, including:

* **KPIs:** Total Sales, Average Sales, Number of Items, Average Rating
* **Visuals:**

  * Sales trend by outlet establishment year
  * Sales by item type and fat content
  * Distribution by outlet size and location type
  * Performance comparison across outlet types

<img width="1337" height="722" alt="blinkit_powerbi_dashboard" src="https://github.com/user-attachments/assets/bb11316e-6c91-4f0a-871c-be1abc016ca1" />


## Key Insights

* **Total Sales:** ₹1.20M
* **Average Sales per Item:** ₹141
* **Best performing outlet type:** Supermarket Type1 with ₹787.55K sales
* **Fat Content Impact:** Regular items contributed more to total sales than low-fat items.
* **Tier-wise Sales:** Tier 3 outlets recorded the highest sales.

## Key Predictions:

* Outlets in Tier 3 cities are expected to continue leading sales growth.
* Regular fat content items are projected to maintain higher contribution than low-fat items.
* Sales show a steady upward trend year-on-year, with seasonal peaks for certain item types.

## How to Use

1. Review the SQL queries in the PDF to understand data cleaning and KPI calculations.
2. Explore the Power BI dashboard to interact with visual insights.
3. Use the queries as a foundation to extend the analysis or adapt to similar datasets.
