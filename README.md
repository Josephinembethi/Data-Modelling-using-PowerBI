This project is a Power BI dashboard designed to analyze and visualize sales performance across multiple dimensions. It highlights key business metrics such as Revenue, Profit, Orders, Profit Margin, and Average Order Value, while providing interactive insights by Year, Region, and Product Category.

Objectives
Track overall sales revenue and profitability.

Monitor order volumes and average order value.

Evaluate profit margins across categories and regions.

Provide interactive filters for dynamic exploration.

Present insights in a clean, professional dashboard layout suitable for business decision‑making.

Tools & Technologies
Power BI Desktop for data modeling and visualization.

DAX Measures for calculations:

Total Revenue = SUM('Sales Data'[Revenue])

Total Profit = SUM('Sales Data'[Profit])

Total Orders = COUNTROWS('Sales Data')

Profit Margin % = DIVIDE([Total Profit], [Total Revenue], 0)

Avg Order Value = DIVIDE([Total Revenue], [Total Orders], 0)

Dashboard Features
KPI Cards: Quick view of Revenue, Profit, Orders, Margin %, and Avg Order Value.

Trend Analysis: Line chart showing revenue trends over time.

Category Insights: Bar chart comparing profit across product categories.

Regional Distribution: Pie chart showing orders by region.

Detailed Table: Drill‑down view of sales data with filters.

Interactive Slicers: Year, Region, and Category filters for dynamic analysis.


Business Value
This dashboard enables managers to:

Quickly assess financial health of the business.

Identify high‑performing categories and regions.

Spot trends and anomalies in revenue and profit.

Make data‑driven decisions with confidence.
