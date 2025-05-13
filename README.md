# Super-Store-Sales-Analysis-Forecast-Dashboard-Power-BI-
This interactive dashboard provides an end-to-end analysis of Super Store sales performance across multiple dimensions such as region, segment, shipping mode, category, sub-category, and time. It also includes a 15-day sales forecasting model.

## Project Objective
The primary objective of this project is to analyze and visualize Super Store sales data to uncover trends, patterns, and performance indicators that support business decision-making. Additionally, the project aims to predict future sales using Power BI’s forecasting capabilities.

## Dataset Used
<a href="https://github.com/yug0537/Super-Store-Sales-Analysis-Forecast-Dashboard-Power-BI-/blob/main/SuperStore_Sales_Dataset.csv">Raw Data<a/>

## Tools & Features Used
- Power BI Desktop
- Data Modeling with relationships using Power Query and DAX
- Time Series Forecasting (15-day prediction using built-in analytics)
- Slicers for regional-level filtering
- Interactive visuals: Line charts, Donut charts, Bar charts, Map visuals

## KPIs
- Total Sales
- Total Profit
- Total Orders
- Average Delivery Time
- Monthly Sales YoY Comparison
- Monthly Profit YoY Comparison
- Sales by Segment, Region, and Category
- Top Performing States
- Sales Forecast (Next 15 Days)

## Dashboard Interaction
<a href="https://github.com/yug0537/Super-Store-Sales-Analysis-Forecast-Dashboard-Power-BI-/blob/main/SuperStore_salesDashboard.pbix">Dashboard<a/>

## Process
- Data Cleaning & Shaping: Used Power Query to clean and transform raw data (e.g., formatting dates, handling nulls, creating derived columns).
- Data Modeling: Established relationships among tables using Power BI’s data model and built a star schema.
- Calculated Measures: Created KPIs using DAX (Total Sales, Total Profit, Orders, Delivery Time).
- Visualizations: Built multiple report pages:
- Overview dashboard with segment, region, category, ship mode.
- Time-series line charts for monthly sales and profit trends.
- Map visualizations for state performance.
- Forecast dashboard for 15-day sales projection.
- Forecasting: Enabled forecasting in the line chart visual using Power BI analytics pane with confidence intervals.

## View Dashboard
<img width="1283" alt="Screenshot 2025-05-14 at 00 37 35" src="https://github.com/user-attachments/assets/667e01ed-0221-4c90-a42b-e592491c70ef" />
<img width="1272" alt="Screenshot 2025-05-14 at 00 38 19" src="https://github.com/user-attachments/assets/8b22bec0-a028-46f3-ab63-349b340d7653" />

## Key Insights
- Total Sales: $1.6M | Total Profit: $175K
- December shows the highest sales and profit, indicating a strong end-of-year demand.
- Consumer segment drives the most revenue (48% of sales), followed by Corporate (33%).
- The West region contributes the most to sales (33%), while the South underperforms slightly.
- Office Supplies and Technology are the highest-selling categories.
-	Top sub-categories: Phones, Chairs, Binders.
- Standard Class is the most used shipping method (~$0.33M in sales), indicating a customer preference for cost-effective delivery.
-	The average delivery time is 4 days, which can be optimized to improve customer satisfaction.
-	The 15-day sales forecast shows fluctuating trends, with expected dips post-holiday season, useful for short-term inventory planning.
-	California, New York, and Texas are top-performing states in sales, indicating high-potential markets for targeted campaign





