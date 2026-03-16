# Pizza Sales Analysis



![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)




![POSTGRESQL](https://img.shields.io/badge/PostgreSQL-4169E1.svg?style=for-the-badge&logo=PostgreSQL&logoColor=white)




![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)




![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)



Pizza Sales Analysis has a comprehensive year's worth of sales data from a fictitious pizza place. The dataset includes detailed information about each order, such as the date and time of purchase, the types of pizzas served, their sizes, quantities, prices.

## Project Structure

    ├── LICENSE
    ├── README.md          <- README for using this project.
    ├── query              <- Code of the DB creation and queries.
    │   └── pizza_sales_db.sql       <- DB creation.
    │   └── query.sql                <- Final queries.
    ├── reports            <- Folder containing the final reports/results of this project.
    │   └── Pizza_Sales_Report.pdf   <- Final analysis report in PDF.
    │   └── query_report.pdf         <- Final query report in PDF.
    ├── src                <- Source for this project.
        ├── data           <- Datasets used and collected for this project.
        ├── pizza_sales_images       <- Additional images for Dashboards.
        ├── data_dictionary.csv      <- Data Dictionary for the dataset.

## Dataset Overview

- **Date and Time**: Recorded for each order to analyze customer behavior and peak hours.
- **Pizza Details**: Includes types, sizes, quantities, prices, and ingredients for each order.

## Analysis

1. **Customer Traffic Analysis**: How many customers visit each day and which times see the highest footfall.
2. **Bestselling Pizzas**: Which pizzas are most popular to inform marketing strategies.
3. **Revenue and Seasonality**: Total revenue over the year and seasonal sales patterns.
4. **Menu Optimization**: Identifying underperforming pizzas for promotions or removal.

## Key Questions Explored

1. **Total Revenue**: Total revenue generated over the period.
2. **Average Order Value**: Average order value throughout the year.
3. **Total Pizzas Sold**: Total number of pizzas sold.
4. **Total Orders**: Total orders placed.
5. **Average Pizzas Per Order**: Average pizzas ordered per order.
6. **Daily Trend for Total Orders**: Sales trend by day of the week.
7. **Monthly Trend for Total Orders**: Monthly trend to analyze seasonality.
8. **% of Sales by Pizza Category**: Contribution of each category to total sales.
9. **% of Sales by Pizza Size**: Contribution of each size to total sales.
10. **Top 5 Best Sellers**: By revenue, quantity, and total orders.
11. **Bottom 5 Lowest Sellers**: By revenue, quantity, and total orders.
12. **Busiest Hours**: Number of customers served each day and peak hours.
13. **Average Orders & Pizzas Per Day**: Daily averages for orders and pizzas sold.

## Summary of Findings

**Most Occupied Days & Month**
- Days: Orders are highest on Friday & Saturday evenings
- Month: Orders peak in January & July

**Sales Performance**
- Category: Classic contributes maximum to sales & total orders
- Size: Large pizza contributes maximum to sales

**Best Sellers**
- Revenue: Thai Chicken Pizza
- Quantity: Classic Deluxe Pizza
- Total Orders: Classic Deluxe Pizza

**Lowest Sellers**
- Revenue, Quantity & Total Orders: Brie Carre Pizza

**Busiest Times**
- Lunch: 12 PM – 1:30 PM
- Dinner: 6 PM – 8 PM

## Author
Pradumn kumar
