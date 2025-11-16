📊 Adidas Sales Insights Dashboard – Power BI
This repository contains an end-to-end Adidas Sales Analysis Dashboard built using Power BI.
The dashboard provides complete visibility into Adidas’ sales performance across regions, products, retailers, and time periods.
It helps in quick decision-making with clear visual storytelling and business-focused KPIs.

📘 📌 Project Overview
The goal of this project is to analyze Adidas' business performance and identify:

Top-performing regions

Best-selling products

High-value retailers

Monthly sales trends

Profitability insights

The dashboard is fully interactive with slicers, drilldowns, and clean brand-focused UI.

📂 Dataset Details
Source: Adidas Sales Dataset (Kaggle)

Total Sales: $900M

Operating Profit: $332M

Operating Margin: 42%

Units Sold: 2 Million

Avg Price Per Unit: $45

The dataset includes:

Region

State

Retailer

Product Category

Units Sold

Total Sales

Operating Profit

Operating Margin

Date

🛠️ Tools & Technologies Used
Power BI Desktop

Power Query (for cleaning & transformation)

DAX (for measures)

Excel/CSV dataset

Star Schema Data Modeling

📈 Key Dashboard Insights
⭐ 1. Overall Performance
Total Sales: $900M

Operating Profit: $332M

Units Sold: 2M

Operating Margin: 42%

📅 2. Monthly Sales Trend
Highest Sales: March ($95M)

Second Highest: December ($92M)

Lowest Sales: April ($57M)

Strong growth in Q1 & Q4

🌍 3. Regional Sales Distribution
West: $270M (30%)

Northeast: $186M

Southeast: $163M

Midwest: $145M

South: $136M

West Region is the top contributor with 30% share.

👟 4. Best-Selling Product Categories
Men’s Street Footwear – $209M

Women’s Apparel – $179M

Men’s Athletic Footwear – $154M

Women’s Street Footwear – $128M

Men’s Apparel – $124M

Women’s Athletic Footwear – $107M

Men’s Street Footwear leads the market.

🛍️ 5. Retailer Performance
West Gear – $243M

Foot Locker – $220M

Sports Direct – $182M

Kohl’s – $102M

Amazon – $78M

Walmart – $75M

West Gear is the top-performing retailer.

🗺️ 6. State-wise Sales Highlights
Top States:

New York – $64M

California – $60M

Florida – $59M

Texas – $46M

Lowest Performing:

Idaho, Georgia, Michigan (< $15M)

🧹 Data Cleaning & Transformation (Power Query)
Removed duplicates

Corrected data types

Created Date hierarchy (Year, Month, Quarter)

Formatted numeric values

Structured tables for modeling

🧮 DAX Measures Used
Total Sales = SUM(Sales[Total_Sales])

Total Units Sold = SUM(Sales[Units_Sold])

Total Profit = SUM(Sales[Operating_Profit])

Avg Margin % = AVERAGE(Sales[Operating_Margin])

Sales LY = CALCULATE([Total Sales], DATEADD(Date[Date], -1, YEAR))

Sales Growth % =
DIVIDE([Total Sales] - [Sales LY], [Sales 
