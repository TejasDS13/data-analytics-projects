# Dairy Goods Sales Analysis with Power BI

This project consists of a two-page interactive report summarizing key business insights.

### Page 1: Sales Overview
![Sales Overview Dashboard] <img width="1309" height="735" alt="image" src="https://github.com/user-attachments/assets/cfa649cf-765c-4479-a8ee-adeb8f6c2706" />


### Page 2: Customer & Location Analysis
![Customer Analysis Dashboard] <img width="1313" height="738" alt="image" src="https://github.com/user-attachments/assets/7eb0638b-9b40-4cb4-af0b-f8283391b5ec" />


## Project Objective

This project aims to analyze a comprehensive dairy dataset to uncover sales patterns, identify top-performing products and brands, and understand the geographic distribution of sales. The goal is to provide actionable insights for business stakeholders.

## Data Source

The analysis is based on a single CSV file, `dairy_dataset.csv`, containing detailed sales and product information.

## Tools Used

- **Power BI / Power Query:** For data cleaning, transformation, and modeling.
- **DAX (Data Analysis Expressions):** For creating custom measures to calculate key performance indicators.

## Key DAX Measures Created

- **Total Revenue:** `Total Revenue = SUM('dairy_dataset'[Approx. Total Revenue(INR)])`
- **Total Quantity Sold:** `Total Quantity Sold = SUM('dairy_dataset'[Quantity Sold (liters/kg)])`

## Key Insights from the Analysis

- **Sales Trend:** The analysis revealed a significant upward trend in revenue during the first half of the year, peaking in May.
- **Top Sales Channel:** The 'Retail' channel is the largest contributor to total revenue.
- **Product Performance:** A detailed analysis identified the top 5 products by both quantity sold and total revenue, highlighting differences between popularity and profitability.
- **Brand Dominance:** The donut chart shows a clear market leader among the brands based on the total quantity of products sold.
- **Geographic Insights:** The map visual pinpoints key cities that are major hubs for revenue generation, offering a clear view of the most important markets.

## How to View the Report

1.  Download the `.pbix` file from this repository.
2.  Open the file using Power BI Desktop.
3.  Interact with the slicers and visuals to explore the data.
