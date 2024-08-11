# README.md

## Overview

This project involves analyzing sales data to derive insights on customer purchasing patterns. We processed and transformed the data to extract meaningful metrics, created pivot tables to visualize trends, and built a custom dashboard to interactively explore our findings.

## Data Processing and Transformation

1. **Initial Data Processing:**
   - Extracted product size from the product details using conditional columns.
   - Trimmed white spaces from product details.
   - Changed the data type of the newly created "Size" column to text.
   - Calculated the "Total Bill" by multiplying quantity and total price, and formatted it as currency.

2. **Transaction Time Handling:**
   - Removed date from the "Transaction Time" by extracting time using text functions.
   - Changed the data type of "Transaction Time" to time.

3. **Date and Time Extraction:**
   - Extracted the day name and month name using date functions.
   - Extracted hours from "Transaction Time" to analyze hourly sales patterns.

4. **Data Loading and Modeling:**
   - Loaded processed data into a sheet and enabled the data model for further analysis.

## Pivot Tables and Analysis

1. **Pivot Tables:**
   - **Hourly Sales Analysis:** Created a pivot table to analyze the count of transaction IDs and total bill by hour.
   - **Daily Sales Analysis:** Created a pivot table to analyze the total bill by day of the week.
   - **Monthly Sales Analysis:** Created a pivot table to analyze the total bill by month.
   - **Product Analysis:** Created pivot tables to analyze the total bill by product category, product type, and store location.

2. **Sorting and Arrangement:**
   - Sorted the days of the week and months chronologically using Power Query and Power Pivot.

3. **Dashboard and Visualization:**
   - Used slicers to build a custom dashboard for interactive exploration.
   - Employed DAX to calculate key metrics such as average sales and average order value.

## Key Findings

- **Sales Patterns:**
  - Identified how sales vary by the hour of the day and day of the week.
  - Analyzed the distribution of total sales across different days of the week and months.

- **Product Insights:**
  - Determined the most frequently ordered size of coffee.

- **Order Metrics:**
  - Calculated the average number of orders per hour and average order value.

## Getting Started

1. **Load Data:**
   - Ensure the dataset is loaded into the data model.

2. **Pivot Table Creation:**
   - Use the provided data model to create pivot tables for various analyses.
   - Apply sorting and formatting as required.

3. **Dashboard:**
   - Utilize slicers and DAX measures to build interactive visualizations and dashboards.

## Future Improvements

- **Expand Analysis:**
  - Incorporate additional data sources or metrics for deeper insights.
  - Explore advanced predictive analytics for sales forecasting.

- **Enhance Visualizations:**
  - Improve visual aesthetics and user interactions in the dashboard.

