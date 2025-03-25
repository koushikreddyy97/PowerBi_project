# PowerBi_project
**Project Documentation: Sales Analysis and Reporting**

## Project Overview
This project involves creating an interactive sales analysis dashboard in **Power BI** to monitor key performance indicators (KPIs) such as **Sales**, **Gross Profit**, **Quantity Sold**, and **Gross Profit Percentage**. The dashboard offers comparisons of current year-to-date (YTD) and previous year-to-date (PYTD) metrics across various dimensions including time, country, and product.

## Objectives
- Track sales performance and profitability.
- Compare current and previous years' performance.
- Provide account-level profitability analysis.
- Enable dynamic visualizations using slicers.

## Steps Involved

1. **Data Ingestion and Transformation**
    - Imported sales, account, product, and date data into Power BI.
    - Applied necessary data transformations using Power Query for cleaning and shaping.
    - Ensured proper data types and removed duplicates.

2. **Data Modeling**
    - Established relationships between dimension and fact tables using primary and foreign keys.
    - Created a **slc_values** table for dynamic selection using slicers.

3. **Measure Creation**
    - Developed key DAX measures including **Sales**, **Gross Profit**, **Quantity**, and **GP%**.
    - Implemented YTD and PYTD calculations using **TOTALYTD** and **SAMEPERIODLASTYEAR** functions.
    - Added comparison measures to analyze YTD vs PYTD performance.

4. **Visualization Development**
    - Designed column charts, scatter plots, and waterfall charts to visualize data.
    - Applied dynamic titles using DAX to reflect slicer selections.

5. **Interactivity**
    - Implemented slicers for selecting **Sales**, **Gross Profit**, or **Quantity**.
    - Enabled tooltips and cross-filtering for enhanced interactivity.

6. **Report Customization**
    - Applied themes and customized visuals for a clean, professional look.
    - Added report-level titles using calculated DAX titles.

## Dashboard Snapshots


Here is a snapshot of the Sales Analysis Dashboard:
![image](https://github.com/user-attachments/assets/d1a4f020-4e1c-4955-bcbc-6688137f621e)

- This chart compares **YTD** and **PYTD** metrics across months for the selected measure.
![image](https://github.com/user-attachments/assets/dba25006-7d11-4e8c-b75e-3f3c59713ab3)

- The scatter plot displays account profitability using **GP%** against the selected measure, highlighting performance.
![image](https://github.com/user-attachments/assets/07facbe7-3fd1-43d2-8646-1134c0b31e8e)

Insights

Sales Performance: The dashboard reveals a steady increase in sales compared to the previous year, with notable growth in key product categories.

Profitability: The scatter plot highlights accounts with low profitability, allowing targeted decision-making.

Regional Analysis: Certain regions show a substantial increase in sales, while others lag, indicating opportunities for improvement.

## Conclusion
This Power BI dashboard offers a comprehensive view of sales performance by leveraging dynamic visualizations and DAX measures. It allows stakeholders to gain insights into profitability trends, monitor key metrics, and make informed decisions.





