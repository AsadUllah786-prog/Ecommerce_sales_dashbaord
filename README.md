🛒 Ecommerce Sales Dashboard
A Year-to-Date Performance & Sales Intelligence Report Built in Power BI

1. Project Overview
The Ecommerce Sales Dashboard is a powerful, interactive Power BI report designed to give a comprehensive Year-to-Date (YTD) view of an ecommerce business's performance. It tracks core KPIs including revenue, profit, quantity sold, and profit margins — with year-over-year (YoY) comparisons — to help stakeholders quickly assess business health.
This dashboard is built for sales managers, business analysts, and executives who need a single source of truth for monitoring ecommerce performance across categories, products, regions, and customer segments.

2. Tech Stack
The dashboard was built using the following tools and technologies:
•	📊 Power BI Desktop – Main data visualization platform used for report creation and interactive filtering.
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing raw ecommerce sales data.
•	🧠 DAX (Data Analysis Expressions) – Used to calculate YTD measures, YoY growth rates, profit margins, and dynamic KPI comparisons.
•	🗺️ Bing Maps Integration – Used for the geographic Sales by State visual, powered by Microsoft Bing.
•	📁 File Format – .pbix for development and .png for dashboard previews.

3. Data Source
The dashboard is built on a structured ecommerce transactional dataset containing order-level sales records across the United States. Key data fields include:
•	Customer region (Central, East, South, West)
•	Product category (Furniture, Office Supplies, Technology)
•	Customer segment (Consumer, Corporate, Home Office)
•	Sales, Profit, Quantity, and Profit Margin values
•	Year dimension — data filtered for the year 2022

4. Features & Highlights
Business Problem
Ecommerce businesses generate enormous volumes of transactional data, but without a centralized reporting layer, it is difficult to answer critical questions quickly:
•	How are sales and profits performing compared to last year?
•	Which product categories or states are underperforming?
•	What are the top-selling products driving the most revenue?
•	How is performance distributed across regions and customer segments?

Goal of the Dashboard
To deliver a real-time, filterable executive dashboard that:
•	Provides instant visibility into YTD sales, profit, quantity, and margin.
•	Enables drill-down by category, year, and region for root-cause analysis.
•	Surfaces top-performing and bottom-performing products for strategic decision-making.
•	Visualizes geographic sales distribution to guide regional strategy.

Walkthrough of Key Visuals
Key KPIs (Top Row)
Four KPI cards span the top of the dashboard, each showing a sparkline trend, current YTD value, and YoY change indicator (green ▲ for positive, red ▼ for negative):
•	YTD Sales: $2.67M — down 77% vs. prior year
•	YTD Profit: $1.34M — up 4.50% vs. prior year
•	YTD Quantity: #107.2K — down 7.29% vs. prior year
•	YTD Profit Margin: 11.58% — up 5.37% vs. prior year
Filters / Slicers
Two interactive slicers at the top-right allow users to filter all visuals simultaneously by Product Category (All, Furniture, Office Supplies, Technology) and Year (2022).
Sales by Category (Table)
A structured table displays a side-by-side comparison of each category's YTD Sales, Previous Year Sales, YoY change, and a Trend indicator. All three categories show significant YoY declines: Furniture (-76.45%), Office Supplies (-77.04%), Technology (-77.55%).
Top 5 Products by YTD Sales (Bar Charts)
Two horizontal bar charts display the top 5 best-selling products — one for high-value items (led by Staple Envelope at $12K and Staples at $11K) and one for lower-value volume products (Epson TM-T88, Belkin 7-Outlet, NeatDesk Desktop, Xerox 1901, Boston 16701 — all at $0.03K).
Sales by State (Map)
An interactive Bing Maps visual plots sales activity across U.S. states, color-coded by customer region (Central, East, South, West). Bubble size indicates sales volume at each location.
YTD Sales by Region (Donut Chart)
A donut chart shows equal 25% distribution across all four regions (Central, East, South, West), each contributing $2.67M — indicating balanced national coverage.
YTD Sales by Segment (Donut Chart)
A second donut chart breaks down sales by customer segment: Consumer (52.07% — $1.39M), Corporate (30.01% — $0.80M), and Home Office (17.92% — $0.48M). Consumer is the dominant segment.

Business Impact & Insights
•	Executive Reporting: Leadership can assess overall business performance at a glance with YTD KPIs and YoY benchmarks.
•	Category Strategy: The Sales by Category table reveals which product lines are declining fastest, helping prioritize inventory or promotional focus.
•	Product Management: The Top 5 Products visuals help merchandising teams double down on best-sellers and retire underperformers.
•	Regional Targeting: The map and region donut help sales teams identify geographic concentration or gaps for campaign planning.
•	Segment Marketing: Knowing that Consumer accounts for 52% of sales allows marketing to tailor messaging and offers accordingly.
