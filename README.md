# Super_Store_Sales_Dashboard
Power BI dashboard to visualize store sales data and provide actionable insights.

## Project Objective

To develop a comprehensive Sales dashboard that
provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze Sales operations effectively.

## DAX Queries

The following Query is used to Create a new column as "Avg. Delivery Days" to calculate the Average duration to deliver a product.

Avg. Delivery Days = DATEDIFF(SuperStore_Sales_Dataset[Order Date], SuperStore_Sales_Dataset[Ship Date],DAY)

## Project Insights

•	Total Revenue: $1.6M

•	Total Profit: $175K

•	Total Units Sold: 22.3K

•	Average Delivery Time: 3.9 Days

•	Highest Revenue Region is West,   contributing 33.37% followed by East with 28.75% of Tota Revenue.

•	Preferred Payment Mode: COD, used by 42.62% of customers.

•	Preferred Shipping Mode: Standard Class, chosen by 58.27% of customers.

•	Largest Customer Segment: Consumer, accounting for 48.09% of Total Segment.

•	Year-over-Year(YoY) Performance: Revenue and Profit increased by 77.3% and 13.4% from 2019 to 2020 respectively.

Developed an interactive Power BI dashboard using store sales data to visualize key metrics such as total revenue, profit, units sold, and delivery times. Analyzed regional performance and customer preferences to provide actionable insights for stakeholders.
