# Sales Performance Analysis using Power BI

**Project Overview**

This project focuses on analyzing sales performance using Microsoft Power BI. The objective is to clean and transform raw sales data, identify regional order distribution, analyze top-performing products, and understand profit trends over time.

The project demonstrates practical skills in data cleaning, data transformation, data visualization, and DAX calculations.The project uses a sales dataset containing approximately 1,020 records and 11 columns.The dataset includes information about sales across four regions: East, West, North, and South.

**Objectives**

- Clean and transform raw sales data using Power Query.

- Identify and handle missing values and duplicate records.

- Analyze order distribution across different regions.

- Identify the top 5 most frequently ordered products.

- Analyze profit trends over time.

- Create calculated tables, calculated columns, and measures using DAX.

**Data Cleaning and Transformation**

Data cleaning was performed using Power Query Editor.

1. Imported the CSV dataset into Power BI.

2. Identified and removed exact duplicate records.

3. Handled missing customer names by replacing null values with "Unknown".

4. Handled missing region and product values.

5. Removed records with missing order dates.

6. Calculated missing numerical values wherever possible using existing dataset relationships.

7. Converted the OrderDate column into the appropriate Date data type.

8. Verified column data types and applied the transformations.

**Dashboard Visualizations**

The dashboard includes three major visualizations.

1. Order Distribution by Region

Visualization through Pie Chart.
Displays the distribution of orders across different regions.
Helps identify regional order patterns.

Top 5 Most Ordered Products

Visualization through Clustered Column Chart.
Displays the five most frequently ordered products.
Uses a Top N filter to identify popular products.

3. Profit Trend Over Time

Visualization through Line Chart.
Displays changes in total profit over time.
Helps understand profit trends across different periods.

**DAX Calculations**

1. Calculated Table – EastRegionOrders

2. Calculated Column – ProfitCostDifference

3. Measure – TotalProfit

**Conclusion**

This project provided practical experience in transforming raw sales data into meaningful business insights using Power BI.
By combining Power Query, data visualization, and DAX calculations, the project demonstrates how business data can be analyzed to understand regional performance, product demand, and profitability trends.
