# Awesome_Choclate_Insight_Report
Project Overview: Awesome Chocolate Sales Dashboard
This dashboard analyzes key metrics for Awesome Chocolate, focusing on sales performance, product profitability, and monthly trends. By examining how each salesperson and product is performing, we aim to get a clear picture of where the company is excelling and where improvements are needed.
# Objective:
Once we have a solid understanding of these areas, we will focus on identifying underperforming areas and provide actionable insights to improve overall performance and profitability.

The goal is to pinpoint issues, such as inconsistent sales, low-performing products, or inefficiencies in shipment, and make data-driven recommendations to boost growth and profitability for Awesome Chocolate.
# Steps Followed 
1. Data Loading
* I imported the sales, shipment, and product data into Power BI Desktop. The dataset includes information about salespeople, products, monthly sales trends, shipment boxes, and profit margins.
2. For Data Cleaning and Transformation
* I used Power Query Editor to clean the data.
* They were checked for missing values, and duplicates especially in key columns like sales, profit, and LBS percentages (LBS stands for low box shipment if the box is shipped ">50" I considered it as a trial box).
* Ensured data consistency across dates and product names.
* Created calculated columns and measures for key metrics such as total sales, total profit, profit percentage, and LBS percentage using DAX.
3. Data Modeling
* After the above process came to the modeling part I set up relationships between different tables (sales, shipments, product performance) to ensure accurate visualizations.
* Defined KPIs such as monthly sales growth, profit targets (if profit is above 0.60 then sales person is moving correctly), and shipment efficiency (LBS %).
4. Creating Visualizations
* Line Chart: I tried to display the trend of monthly sales performance over time to identify growth or dips with that growth and dips I created tooltips to visualize how sales are breaking down into different countries.
* Bar Chart: Showed the distribution of shipments by the number of boxes to understand the scale of each shipment.
* Gauge Chart: Visualized overall performance with a gauge, indicating whether the sales and profit targets are being met.
* Table Visuals: Summarized salesperson and product performance, including key metrics like total sales, profit, profit percentage, and LBS percentage.
5. Target Indicators and Conditional Formatting
* Added conditional formatting to the sales and product performance tables to visually highlight whether salespeople or products meet their targets.
* I used color coding to differentiate between those on target (green) and below target (red).
6. Interactivity and Slicers
* I also Included slicers for categories such as product type (e.g., Bars, Bites), region (e.g., USA, Canada), and period to allow easy filtering and comparison of sales across different dimensions.
7. Testing and Refinement
* Tested the dashboard by applying different filters and slicers to ensure data accuracy and visualization clarity.
* Refined visuals, ensuring the design is easy to interpret while providing a comprehensive overview of sales and performance.
8. Publishing
* The report was then published to Power BI Service.
# Snapshot of Dashboard (Power BI Service)

![Screenshot 2024-09-24 114101](https://github.com/user-attachments/assets/5885ff7f-b87c-47ea-9349-2762b05ba3bf)
Insights :
I created a new measure to show multiple KPIs using a card visual. This allows me to display key performance indicators (KPIs) such as total sales, total profit, profit percentage, and LBS percentage
1. Sales Overview (Top Section)
* Total Sale: $17M (with a Month-over-Month decrease of -10.3%)
* Total Boxes Shipped: 1M
* Total Shipments: 3K
* Total Cost: $7M
* Total Profit: $10M
* Profit Gauge: Shows 60.9% profit, likely indicating a healthy profit margin relative to costs.
2. Sales by Month 
* Line chart displays monthly sales trends from March 2023 to January 2024.
* Key observation: The sales fluctuate over time, peaking in May 2023 and again in November 2023, with noticeable dips in other months.
3. Shipments by Boxes
* A histogram visualizes the distribution of box shipments. Most shipments are below 500 units, but there are outliers above 1500.
4. Salesperson Performance Table
 Columns include:
* Salesperson 
* Sales 
* Profit 
* Profit Percentage
* LBS Percentage
* Target Status (Highlighted in red or green to show whether the target is met or missed)
Key performers:
* Brien Boise: Leads with the highest profit margin at 69.1% and on-target performance.
* Other notable performers include Barr Faughny (61.2%) and Camilla Castle (61.3%), who are also on target.
5. Product Performance Table
  Columns include:
* Product Name
* Sales, Profit, and Profit %
* LBS %
Target Status
High-performing products:
* 99% Dark & Pure: Highest sales ($1.97M) and a profit margin of 74%.
* Other strong performers include Almond Choco and Fruit & Nut Bars, both on target.
6. Target Indicators
* The rightmost columns of the tables show a visual status of "On Target" (green) or "Below Target" (red) based on the profit percentage.
* This feature provides a quick snapshot of who or what products are performing well and which need attention.

# Conclusion and Suggestions for the Awesome Chocolate Dashboard Project
The dashboard provides a clear and comprehensive picture of Awesome Chocolate's sales performance, product success, and shipment efficiency By analyzing key metrics such as total sales, profit margins, and shipment LBS percentages, we can see how well each salesperson and product line is performing. Additionally, the monthly sales trends give a clear picture of the company's growth trajectory.

Key insight:
* As we can see salespeople and products are underperforming and falling below target, indicating areas where improvements can be made.
* Top-performing products such as the "99% Dark & Pure" are driving significant profit, while others are struggling to meet targets.
* The shipment efficiency measured by LBS percentage is critical, with certain regions or product lines needing more optimization in logistics and box usage.

Suggestions:
* Focus on Low-Performing Salespeople: Offer additional training, resources, or support to salespeople falling below their profit targets. Understand any challenges they may be facing.
* Product Strategy: Products that are not meeting sales targets, like "85% Dark Bars" or "Baker’s Choco Chips," might need changes in marketing or pricing to help boost sales. We could also try special offers or   bundle deals to attract more customers. By promoting what makes these products special and offering better prices or discounts, we can make them more appealing and increase sales.
* Seasonal Promotions: We can also offer discounts, bundle deals, or limited-time offers during dips of month and holidays or special occasions to maintain & drive sales.

                                                                                                                    Thank You






















