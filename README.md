# Car Sales Dashboard

#### 1. Car Sales Analytics:
Car Sales & Market Insights Dashboard. A dynamic, interactive Power BI dashboard designed to analyze end-to-end car sales performance—focusing on Year-to-Date (YTD) metrics, year-over-year growth, regional dealer performance, and product trends (body style, color, etc.).

#### 2. Purpose:
This dashboard provides a comprehensive overview of sales activities for a car dealership network. It tracks key performance indicators (KPIs) like Total Sales, Average Price, and Cars Sold, comparing current performance against the previous year (YoY). The tool is intended for sales managers and stakeholders to identify best-performing dealers, monitor weekly sales trends, and uncover profitable vehicle segments.

#### 3. Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – The primary tool for data visualization and report design.

📄 Excel – Used as the raw data source (flat file) containing the car sales records.

🧠 DAX (Data Analysis Expressions) – Extensive use of time-intelligence functions (e.g., TOTALYTD, SAMEPERIODLASTYEAR, TOTALMTD) to calculate YTD Sales, YoY growth percentages, and dynamic conditional formatting for KPI cards (Green/Red indicators).

📂 Power Query – Used for data connectivity, transformation, and cleaning (ETL) to ensure data quality (e.g., replacing values, checking column quality).

📅 Date Table – A custom calendar table created using DAX to support accurate time-intelligence calculations across the dataset.

#### 4. Data Source
Source: Kaggle (Car Sales Dataset)

The project utilizes a primary data table containing approximately 25,000 rows of transactional data. Key columns include:

Sales Details: Order Date, Price (Sales Amount), Car ID.
Product Details: Company (Make), Model, Body Style, Color, Engine, Transmission.
Customer & Dealer: Customer Name, Dealer Name, Dealer Region.

#### 5. Features:
Business Problem: Monitoring year-over-year growth and weekly trends in a competitive car market is difficult without centralized data.

Stakeholders need to quickly answer:

Is our year-to-date revenue growing compared to last year?
Which vehicle body styles (e.g., SUV, Sedan) are driving the most sales?
How are different dealer regions performing?

Goal of the Dashboard: To provide a centralized view of sales health that enables:

Real-time monitoring of YTD Sales, Average Price, and Cars Sold.
Identification of sales peaks through weekly trend analysis.
Strategic decision-making regarding inventory and dealer performance.

Walkthrough of Key Visuals:

KPI Banner (Top):

Displays YTD Total Sales, YTD Average Price, and YTD Cars Sold.
Includes Month-to-Date (MTD) metrics and Year-over-Year (YoY) Growth % with dynamic color-coded icons (Green for positive growth, Red for decline).

YTD Sales Weekly Trend (Area Chart):

Visualizes the weekly sales trend to identify peak selling weeks. Includes a dynamic "Max Point" marker to highlight the week with the highest sales.

Sales Distribution (Donut Charts):

Sales by Body Style: Breakdown of revenue by vehicle type (SUV, Hatchback, Sedan, etc.).
Sales by Color: Analyzes consumer color preferences (e.g., Pale White, Black, Red).

Sales by Dealer Region (Map):

A bubble map visualization where bubble size represents the volume of cars sold in different dealer regions (e.g., Austin, Scottsdale, Janesville).

Company-Wise Sales Trend (Matrix Table):

A detailed grid showing sales performance by car manufacturer (e.g., Chevrolet, Ford, Dodge).
Includes data bars for a quick visual comparison of sales volume and average price.

Details Grid (Page 2):

A granular transactional view allowing users to see row-level details for every car sold, exportable for further analysis.

Business Impact & Insights:

Growth Tracking: Immediate visibility into YoY growth helps assess if sales targets are being met (e.g., a 23% increase in revenue).
Inventory Optimization: "Sales by Body Style" helps in understanding demand, suggesting more inventory is needed for SUVs vs. other categories.
Dealer Performance: The map visualization highlights high-performing regions, guiding resource allocation and marketing focus.

#### 6. Screenshots:

![Dashboard Preview](https://github.com/chinmai-budati/Car-Sales-Dashboard/blob/main/Images/Overview%20Page.png)

![Dashboard Preview](https://github.com/chinmai-budati/Car-Sales-Dashboard/blob/main/Images/Details%20Page.png)
