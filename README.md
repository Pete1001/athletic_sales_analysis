
# Athletic Sales Analysis

## Overview
This project involves analyzing sales data from two datasets (2020 and 2021) related to athletic products sold by various retailers across different regions, states, and cities. The focus is on identifying trends in total sales, women's athletic footwear sales, and top-selling retailers.

## Data
- **athletic_sales_2020.csv**: Contains sales data for the year 2020.
- **athletic_sales_2021.csv**: Contains sales data for the year 2021.

The datasets include information such as retailer names, product types, sales methods (e.g., in-store, online), regions, and total sales.

## Objectives
The main objectives of the analysis are:
1. Combine and clean the sales data for 2020 and 2021.
2. Determine which regions and retailers sold the most products and generated the most sales.
3. Focus on women's athletic footwear sales and analyze which retailers had the most sales in this category.
4. Identify the top days and weeks for women's athletic footwear sales.

## Steps and Key Insights

### 1. Combine and Clean the Data
- The two datasets were combined, and the `invoice_date` column was converted into a datetime format for further time-based analysis.

### 2. Determine the Region with the Most Sales
- Using `groupby` and `pivot_table`, the data was grouped by region, state, and city to identify which regions sold the most products and generated the most total sales.

### 3. Determine the Retailer with the Most Sales
- A similar grouping method was used to identify the top retailers based on total sales and total women's athletic footwear sales.

### 4. Time-based Sales Analysis
- The sales data was resampled into daily and weekly bins to identify the most profitable days and weeks for women's athletic footwear.

## Tools Used
- **Python**: For data processing and analysis.
- **Pandas**: For manipulating and aggregating the sales data.

## How to Use
1. Clone this repository.
2. Ensure the required datasets (`athletic_sales_2020.csv` and `athletic_sales_2021.csv`) are in the same directory.
3. Run the Jupyter notebook to generate the analysis and insights.
4. The final outputs include the top-performing regions, retailers, and sales periods.

## Conclusion
This analysis provides key insights into athletic sales trends across different regions and helps identify top-performing retailers and product categories, particularly focusing on women's athletic footwear.
