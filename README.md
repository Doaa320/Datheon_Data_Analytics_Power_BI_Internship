Datheon Data Analytics & Power BI Internship - Task 2
Executive Sales & Profit Performance Dashboard
Project Overview
This project presents an interactive Executive Sales & Profit Dashboard built using Power BI to evaluate corporate sales performance, profitability trends, and customer segments, aiming to extract actionable business insights to support strategic decision-making.

Executive Summary & Core Metrics
Total Revenue: $2,297,201

Total Profit: $286,397

Overall Profit Margin: 12.47%

Total Orders: 9,994 completed purchase orders

Average Order Value (AOV): $229.86 per transaction

Total Quantity Sold: 37,873 units

Key Numerical Insights & Breakdowns
1. Category Profitability
Technology: Revenue of $836,154 and Profit of $145,455 (High profit margin of 17.4%).

Furniture: Revenue of $741,999 and Profit of $18,451 (Low profit margin of 2.5% due to high discounts).

Office Supplies: Revenue of $719,047 and Profit of $122,491 (17.0% profit margin).

2. Regional Revenue Split
West Region: Leader with total sales of $725,458 and profit of $108,418.

East Region: Sales of $678,781 and profit of $91,523.

3. Returns & Cancellations Impact
Recorded a return and cancellation rate of 5.9% of total revenue, causing an estimated revenue leak of $135,535.

Extended Metrics & Behavioral KPIs
1. Customer Segment Breakdown
Corporate Segment: Contributes 30.2% of total sales with high demand stability.

Consumer Segment: Represents the largest share of purchase transactions at 51.8% of total orders.

Home Office: Records a competitive average basket size accounting for 18% of total revenues.

2. Discount Impact Analysis
Transactions exceeding a 20% discount threshold resulted in a net profit drop exceeding 40% in the Furniture category, indicating the need to restructure seasonal discounting policies.

3. Time-Series & Seasonal Trends
Peak Revenue Month: November (driven by holiday sales and year-end promotions) with a growth rate of 24.5% compared to the annual monthly average.

Average Shipping Speed: 3.9 business days as the average delivery timeframe using standard shipping methods.

Technical Implementation & Workflow
Data Cleaning & Transformation: Executed via Power Query to standardize transaction schemas, handle null values, and structure precise date dimensions.

Data Modeling: Designed a clean relational Star Schema, establishing one-to-many (1:*) relationships and hiding technical keys to optimize the user experience.

DAX Measures Used:

Total Sales = SUM(Sales[Amount])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Average Order Value = DIVIDE([Total Sales], COUNT(Sales[Order_ID]), 0)

Visual Design: Styled with a clean executive aesthetic featuring minimalist light backgrounds contrasted with dark indicators for intuitive metric tracking
