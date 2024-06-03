# Sales Performance Report Dashboard 
Overview
The Sales Performance Report Dashboard provides a comprehensive analysis of sales and profit metrics, enabling stakeholders to track performance, identify trends, and make data-driven decisions. The dashboard features various visualizations and metrics calculated using DAX formulas, offering both high-level overviews and detailed breakdowns.

Key Metrics
Total Sales: The aggregate sales value over the selected period.
Total Profit: The total profit generated, calculated as the difference between total revenue and total costs.
Sales YoY%: Year-over-Year percentage change in sales, indicating growth or decline compared to the previous year.
Profit YoY%: Year-over-Year percentage change in profit, providing insights into profitability trends.
Visualizations
Monthly Sales by Month: A line or bar chart displaying sales for each month, helping to identify seasonal trends and monthly performance variations.
Weekly Sales: A chart showing sales on a weekly basis, useful for short-term trend analysis and identifying weekly patterns.
Top 10 Products: A bar chart or table highlighting the top 10 products by sales, allowing for quick identification of best-sellers.
Sales by Brand Name: A breakdown of sales distributed across different brands, showcasing the performance of each brand.
Sales by Channel: Visualization of sales split by various channels (e.g., online, retail), providing insights into channel performance.
Profit by Channel: A detailed view of profit margins across different sales channels, aiding in the assessment of channel profitability.
Top 10 Sales by State: A chart or map highlighting the top 10 states by sales, offering geographical insights into sales distribution.
Sales by Promotion Name: Analysis of sales generated from different promotions, helping to evaluate the effectiveness of marketing campaigns.
Slicers
To enhance the interactivity and usability of the dashboard, several slicers are implemented:

Year: Allows users to filter the data by specific years.
Date: Enables selection of custom date ranges for more precise analysis.
Brand Name: Filters the data to show metrics related to specific brands.
State Zone: Provides the ability to drill down into sales data by geographical zones.
DAX Formulas
The following DAX formulas are utilized to compute the key metrics:

Total Sales: SUM(Sales[Sales Amount])
Total Profit: SUM(Sales[Profit])
Sales YoY%: DIVIDE([Total Sales], CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date])))-1
Profit YoY%: DIVIDE([Total Profit], CALCULATE([Total Profit], SAMEPERIODLASTYEAR('Date'[Date])))-1
Insights and Actionable Items
Identify High-Performing Products: Use the top 10 products visualization to focus on best-sellers and strategize inventory and marketing efforts.
Analyze Seasonal Trends: Monthly and weekly sales charts help in understanding seasonal demand and planning accordingly.
Channel Strategy: Sales and profit by channel visualizations provide clarity on which sales channels are performing well, assisting in resource allocation and strategic planning.
Geographical Performance: Sales by state and zone slicers enable regional performance analysis, helping in targeted marketing and sales efforts.
Promotion Effectiveness: Evaluate the success of different promotions to optimize future marketing campaigns.
Conclusion
This Sales Performance Report Dashboard is a powerful tool for monitoring and analyzing sales and profit metrics. The interactive slicers and detailed visualizations allow stakeholders to drill down into specific data points, facilitating informed decision-making and strategic planning.

