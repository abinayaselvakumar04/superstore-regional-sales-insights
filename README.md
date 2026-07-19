Overview

This repository contains a Tableau workbook that consolidates Super Store transactional data into a single interactive dashboard. It is designed to help analysts and business stakeholders monitor overall sales and profit performance, compare category and sub-category contributions, evaluate regional sales distribution, and track quantity trends across months.

Key Metrics Tracked


Sum of Sales – Total sales value across all transactions
Average of Profit – Average profit earned per transaction
Sum of Profit – Total profit generated across all transactions
Category Wise Sales – Sales distribution across Furniture, Office Supplies, and Technology
Sales Wise Region – Percentage share of sales contributed by each region
Region Wise Sales – Ranked sales performance across all regions, including Central, South, North, Oceania, and others
Month Wise Quantity – Quantity sold trend across reporting months
Subcategory Wise Sales – Sales performance broken down by product sub-category with cumulative percentage trend
Product Wise Sales – Comparative sales and shipping cost analysis at the product level


Dashboard Features


Interactive filters for Category and Region to control the entire report
Horizontal bar chart for category-wise sales comparison
Donut chart showing percentage-wise sales contribution by region
Ranked vertical bar chart for region-wise sales performance
Step line chart tracking month-wise quantity sold
Combination chart (bar and Pareto line) for sub-category sales and cumulative contribution
Bubble chart comparing product-wise sales against shipping cost


Data Fields Used

FieldDescriptionOrder IDUnique identifier for each orderOrder DateDate on which the order was placedCategoryProduct category (Furniture, Office Supplies, Technology)Sub-CategoryProduct sub-category within each categoryRegionSales region (Central, South, North, Oceania, and others)SalesSales value generated from the orderProfitProfit earned from the orderQuantityNumber of units sold in the orderShipping CostCost incurred for shipping the order

Tools Used


Tableau Desktop – Dashboard design and visualization
Tableau Calculated Fields – Custom metrics for profit averages and percentage contributions
Filters and Parameters – Interactive controls for category and region-based analysis


How to Use


Clone or download this repository.
Open the .twbx workbook file in Tableau Desktop or Tableau Reader.
Use the Category and Region filters at the top of the dashboard to refine the view.
Hover over chart elements to view detailed tooltips with underlying values.
Use the scroll bar to access additional visuals, including Month Wise Quantity, Subcategory Wise Sales, and Product Wise Sales.


Potential Future Enhancements


Add year-over-year sales and profit comparison
Include customer segment-based performance analysis
Incorporate discount impact analysis on profit margins
Add shipping mode and delivery time performance tracking


License

This project is intended for educational and portfolio demonstration purposes.

Author

Prepared as part of a data analytics portfolio project focused on Tableau-based retail business intelligence reporting.
