# Sales-Analysis

## Table of Contents
- [Project Overview](project-overview)
- [Data Visualizations](data-visualizations)
- [Insights](insights)
  
### Project Overview
This data analysis project seeks to analyze and understand the 2019 sales performance of a fictional company. It further seeks to investigate the product sales behind the increase/decrease of revenue across the months for all cities.

### Data Sources
The ‘sales_data.csv’ file is the primary dataset used for this analysis. It contains all the necessary details about each sale made by the company.

### Tools
Excel – Data Cleaning, Analysis and Visualization

### Data Cleaning/Transformation
In this file, I performed the following data-cleaning tasks:
-	Checking/Removing duplicates
-	Splitting columns
  
### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions such as:
-	What is the overall revenue trend?
-	What are the peak sales periods?
-	Which products are top-sellers?
-	By how much percentage did revenue increase/decrease compared to the previous month?
  
### Data Analysis
Interesting code/features worked with:
-	Pivot tables
-	Lookup Functions
  
```excel
=VLOOKUP('Pivot Table'!$F$3,'Product Decrease'!$C$3:$V$15,R$1,FALSE)
```

### Data Visualization
1. Revenue Trend: This line chart shows the revenue trendline for each city(ies).
2. %Revenue MOM: This waterfall chart shows the % increase/decrease in revenue for each city compared to the previous month.
3. Product sales MOM: This gives deeper insight into the %Revenue MOM chart. It shows the products that drove the increase/decrease in revenue.
4. %Revenue split by city: Tthis doughnut chart shows the percentage of revenue from each city at a particular month.
5. Best-selling products: This treemap displays in hierarchy, the best-selling products based on order quantity.

### Insights
-	The best-selling products contribute almost nothing to revenue. Cheap products have many buyers.
-	A greater percentage of revenue comes from San Francisco
-	Huge sales decrease recorded in June across all cities.
