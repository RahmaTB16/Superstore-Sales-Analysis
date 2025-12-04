# Superstore Sales Analysis

**Author:** Rahma Touaibi  
**Date:** December 4, 2025

## Description
A full analysis of the Sample Superstore dataset including data cleaning, KPI calculation, exploratory data analysis, and visualizations to provide actionable business insights.

## Dataset

**File:** Sample_Superstore.csv  

**Description:** This dataset contains sales records from a sample superstore.  
Columns include:
- Order ID, Customer ID, Product ID
- Order Date, Ship Date, Ship Mode
- Customer and Product details (Name, Category, Sub-Category)
- Sales, Quantity, Discount, Profit

**Notes:**  
- Dates are in MM/DD/YYYY format.  
- Profit ratio is calculated in the analysis.  
- Some orders may have very high sales or negative profit (returns or discounts).

## Tools & Libraries
- R  
- dplyr  
- ggplot2  
- lubridate  
- scales  
- ggcorrplot  

## Key KPIs
**Key KPIs calculated:**  
- Total Sales  
- Total Profit  
- Profit Margin

## Visualizations
**Visualizations included:**  
- Sales by Category  
- Sales by Region  
- Sales per Month  
- Correlation Heatmap  
- Profit vs Sales  
- Profit by Category (Boxplot)

## Insights & Recommendations
- Technology products and West region drive the highest sales.  
- Sales peak in November, drop mid-year.  
- Focus marketing and inventory on top categories.  
- Reduce excessive discounts to improve profitability.  
- Optimize product mix and expansion in high-performing regions.

## How to Run
Open the R Markdown file (`Superstore_Analysis.Rmd`) in RStudio and knit to HTML to view the full report with code, outputs, and plots.

## Visualizations
All project visualizations are included in the compressed file: [visualizations.zip](visualizations.zip)

