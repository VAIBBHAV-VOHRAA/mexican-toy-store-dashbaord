
# Mexican Toy Stores Performance & Inventory Analysis Dashboard

## Purpose
This Power BI project provides a comprehensive executive overview of performance and inventory metrics for a fictional chain of Mexican toy stores (Maven Toys). The dashboard is designed to help stakeholders monitor key financial indicators—such as revenue, profit, and profit margins—while also identifying top-selling products and tracking monthly sales trends. Furthermore, it offers deep insights into inventory management, highlighting stores with high or medium out-of-stock risks to ensure optimal stock levels and prevent lost sales.

## Dashboard Previews

### Executive Overview - Performance Dashboard
![Executive Overview Dashboard](https://raw.githubusercontent.com/VAIBBHAV-VOHRAA/mexican-toy-store-dashbaord/main/MTSR.PAGE1.png)

### Inventory & Store Performance
![Inventory Performance Dashboard](https://raw.githubusercontent.com/VAIBBHAV-VOHRAA/mexican-toy-store-dashbaord/main/MTSR.PAGE2.png)

## Tech Stack

## Tech Stack
*   **SQL:** Data extraction and preliminary exploration .
*   **Power BI Desktop:** Dashboard creation, data visualization, and reporting.
*   **Power Query:** Data cleaning, transformation, and shaping.
*   **DAX (Data Analysis Expressions):** Creating calculated columns and measures for advanced metrics (e.g., Profit Margin %, Average Revenue per Store, Days of Supply).
*   **Data Modeling:** Establishing relationships between sales, products, stores, and inventory tables.
*   **File Formats:** `.pbix` for development and `.png` for dashboard previews.

## Data Source
*   **Kaggle:** The dataset simulating sales and inventory data for "Maven Toys" stores in Mexico.

## Features and Highlights

### Business Problem
Maven Toys needs to understand its overall financial health across different store locations and product categories. Additionally, they face challenges in inventory management—specifically, identifying stores that are at risk of running out of stock for popular items, which directly impacts potential revenue.

### Goal of the Dashboard
The primary goal is to empower executives and regional managers with actionable insights into:
1.  Overall sales performance (Revenue, Profit, Margin).
2.  Product performance (Top Sellers by Revenue).
3.  Sales trends over time to identify seasonality.
4.  Inventory health, specifically flagging stores and products with low "Days of Supply" indicating a high risk of stockouts.

### Walkthrough of Key Visuals

**Page 1: Executive Overview - Performance Dashboard**
*   **KPI Cards:** High-level metrics showing Total Revenue ($14.44M), Total Profit ($4.01M), Profit Margin % (27.79%), and Total Units Sold (1M).
*   **Donut Chart (Total Revenue by Product Category):** Illustrates the revenue distribution, highlighting 'Toys' as the dominant category (35.26%), followed by 'Electronics' and 'Art & Crafts'.
*   **Matrix Table (Top 5 Best Sellers):** Details the top-performing products by revenue, including specific profit and unit sales figures (e.g., Lego Bricks leading the pack).
*   **Area Chart (Total Revenue and Total Profit by Month):** Displays the monthly trend, showing relatively stable performance early in the year with a noticeable dip around October/November before recovering slightly in December.
*   **Slicers:** Allow filtering by Store Location, Product Category, and Year.

**Page 2: Inventory & Store Performance**
*   **Combo Chart (Total Revenue VS Average Revenue by Store Locations):** Compares total revenue against the average revenue per store across different location types (Downtown, Commercial, Residential, Airport). Downtown stores generate the highest total revenue. But highest average revenue is coming from Airport with only 3 stores open at the moment . This clearly indicates more stores needs to be opened in Airport location which can be very profitable for the company.
*   
*   **Scatter Plot (Units sold per day VS stock in hand):** A crucial visual for risk assessment. It categorizes inventory into 'High Risk (< 1 week)', 'Medium Risk (1-2 weeks)', and 'Out of Stock' based on the daily sales rate versus current stock.
*   **Table (Stock in hand & days of supply by Store):** Provides a granular view of inventory health per specific store location, using color-coding (conditional formatting) on the 'days of supply' to easily spot healthy (green) vs. concerning inventory levels.
*   **Slicer:** Allows filtering by specific Store Name to drill down into localized inventory issues.

### Business Impact and Insights
*   **Product Focus:** The 'Toys' category is the primary revenue driver. Marketing and inventory efforts should prioritize keeping top sellers like 'Lego Bricks' and 'Colorbuds' (Electronics) well-stocked.
*   **Location Strategy:** 'Downtown' locations are the highest revenue generators. But Airport locations generate the maximum average revenue.  Expansion in Airport location might yield the best ROI.
*   **Inventory Optimization:** The scatter plot reveals several items in the 'High Risk' and 'Out of Stock' categories. By utilizing the 'days of supply' metric, supply chain managers can proactively reorder stock for specific stores (e.g., those dipping below 1-2 weeks of supply) to prevent stockouts of high-velocity items, thereby protecting revenue streams.
*   **Trend Analysis:** The dip in Q4 sales (October/November) requires further investigation to understand the cause and develop strategies to mitigate it in future years.


