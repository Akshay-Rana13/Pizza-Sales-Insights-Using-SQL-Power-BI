# Pizza-Sales-Insights-Using-SQL-Power-BI
## Overview
The Pizza Sales Dashboard provides insights into pizza sales performance, including revenue, order trends, and best-selling/worst-selling pizzas. It visualizes key performance indicators (KPIs) and sales trends using various charts. This project was completed using SQL and Power BI.

## KPI Requirements
- The following KPIs are displayed on the dashboard:
- Total Revenue: The total revenue generated from pizza sales.
- Average Order Value: The average amount spent per order.
- Total Pizzas Sold: The total number of pizzas sold.
- Total Orders: The total number of distinct orders placed.
- Average Pizzas Per Order: The average number of pizzas per order.

## Charts Requirement
The dashboard includes the following visual representations:
#### Sales Trends
- Daily Trend for Total Orders: Shows order volume across different days of the week.
- Monthly Trend for Orders: Displays order trends across different months of the year.

#### Sales by Category & Size
- % of Sales by Pizza Category: Represents the percentage of total revenue contributed by each pizza category.
- % of Sales by Pizza Size: Shows the sales contribution by different pizza sizes.
- Total Pizzas Sold by Pizza Category: Displays the total number of pizzas sold per category.

#### Best & Worst Performing Pizzas
- Top 5 Pizzas by Revenue: Lists the top five pizzas generating the highest revenue.
- Bottom 5 Pizzas by Revenue: Lists the five pizzas with the lowest revenue.
- Top 5 Pizzas by Quantity: Shows the five best-selling pizzas by quantity sold.
- Bottom 5 Pizzas by Quantity: Displays the least sold pizzas.
- Top 5 Pizzas by Total Orders: Lists the pizzas with the most total orders.
- Bottom 5 Pizzas by Total Orders: Shows the pizzas with the least total orders.

## SQL Queries Used
The dashboard data is generated using SQL queries from the Pizza Sales SQL Queries document. The queries extract information from the pizza_sales database to calculate KPIs and generate chart data. <a href="https://github.com/Akshay-Rana13/Pizza-Sales-Insights-Using-SQL-Power-BI/blob/main/PIZZA%20SALES%20SQL%20QUERIES.docx">SQL Queries</a>

## Power BI Implementation
- The extracted SQL data was imported into Power BI for visualization. The following steps were performed:
- Data cleaning and transformation using Power Query.
- Creating relationships between tables where necessary.
- Designing interactive dashboards using various visualizations like bar charts, pie charts, and trend graphs.
- Implementing slicers and filters for better data exploration.

## Dashboards
![Pizza sales Dashboard](https://github.com/user-attachments/assets/36146976-8f40-4d00-960a-4115336bec15)
![Pizza sales Dashboard 2](https://github.com/user-attachments/assets/1d173ea5-5343-4631-bace-78473ea9f725)

## Insights from the Dashboard
- Orders are highest on Friday and Saturday evenings.
- July and January have the highest order volumes.
- The Classic pizza category contributes the most to sales.
- Large size pizzas generate the most revenue.
- The Thai Chicken Pizza generates the highest revenue.
- The Brie Carre Pizza performs the worst in sales.

## Conclusion

The Pizza Sales Dashboard effectively provides valuable insights into sales trends, revenue generation, and best-selling/worst-selling pizzas. By leveraging SQL for data extraction and Power BI for visualization, this project enhances decision-making in the food industry. The analysis highlights key trends that can be used to optimize menu offerings, pricing strategies, and marketing efforts.
