# Power BI Sales Analysis Dashboard

## Project Overview
This project focuses on analysing sales performance using Microsoft Power BI. The goal was to bring key sales metrics into one interactive dashboard and make it easier to explore performance across products, customers, and time.
Rather than looking at revenue alone, I included measures such as profit, cost of goods sold (COGS), and profit margin to provide a broader view of business performance. I also explored how profit varies across product brands and customer income levels, how costs differ by product colour, and how revenue and customer activity change over time.
The project covers the process of preparing data for analysis, reviewing the data model, developing measures, and building interactive visualisations that support business reporting.

## Project Objectives
- Monitor overall revenue, profit, cost of goods sold, customer count, and profit margin.
- Compare profitability across product brands.
- Examine how cost of goods sold varies across product colours.
- Explore profit across customer income levels.
- Track monthly revenue and customer activity.
- Allow users to filter the dashboard by product, region, and gender.
- Present sales information in a format that supports business monitoring and further investigation.

## Tools and Technologies
- Microsoft Power BI Desktop: Data modelling, DAX measures, and dashboard development.
- Power Query: Data inspection and preparation, where applicable to the transformations performed.
- DAX (Data Analysis Expressions): Measures used to calculate and display key performance indicators.
- Power BI Model View: Reviewing the data model and table relationships.

## Data Cleaning
Before developing the report, the data needed to be reviewed to establish whether its structure and fields were suitable for analysis.
The cleaning stage focused on identifying data-quality issues that could affect calculations, comparisons, and visualisations.
The checks relevant to this project include:
- Reviewing the available tables and their columns.
- Checking data types, particularly for numerical measures and date fields.
- Inspecting missing or blank values in fields required for analysis.
- Looking for inconsistent values in product and customer attributes.
- Reviewing numerical fields used for revenue, profit, and cost calculations.
The purpose of this stage is to reduce the risk of presenting misleading results due to inconsistent or unsuitable data.

## Data Modelling
<img width="1158" height="702" alt="Sales data model" src="https://github.com/user-attachments/assets/0ad4efdd-50f1-432e-b6ba-77d8a25db248" />

The report uses Sales, Products, Customers, and DateTable as its main analytical tables.
The data model is important because the dashboard combines sales measures with descriptive attributes. For example, profit is analysed by product brand and customer income level, while revenue and customer activity are examined over time.
The modelling stage focuses on: Examining table relationships in Power BI Model view. A well-structured model helps make a report easier to maintain and reduces the need to create separate datasets for every visual.

## Dashboard Design and Visualisations
The report brings together financial KPIs, product comparisons, customer analysis, and monthly trends on a single dashboard page.
<img width="1307" height="740" alt="Screenshot 2026-10-22 143607" src="https://github.com/user-attachments/assets/08e9bbf9-46b0-45b0-8a2c-366797c61bd0" />

### 1. KPI Cards
The KPI cards display:
- Revenue
- Profit
- Cost of Goods Sold
- Customers
- Profit Margin
These cards give users a quick overview of the selected data before they examine the detailed charts.

### 2. Brand by Profit
This chart compares profit across product brands.
It helps users identify which brands contribute more or less to the profit shown in the report. These differences can be used to guide further investigation into product performance, sales volume, pricing, and costs.

### 3. Purchase Cost by Color
This visual compares cost of goods sold across product colours.
It provides a way to explore how recorded costs are distributed among the colour categories in the dataset. The chart shows a cost comparison; it does not, by itself, establish that colour causes higher or lower costs.

### 4. Profit by Income Level
This visual examines profit across customer income-level categories.
It allows users to explore how profit is distributed across those categories and identify patterns that may warrant further analysis.

### 5. Monthly Revenue Trend
The line chart tracks revenue over time.
It helps users observe changes in monthly revenue, identify periods of stronger or weaker performance, and investigate possible seasonal or operational patterns.
Additional information would be needed to explain why revenue rises or falls.

### 6. Monthly Customers
This chart displays the customer metric by month.
It allows users to compare customer activity over time and explore whether changes in customer numbers occur alongside changes in revenue.
The interpretation depends on how the underlying customer measure is calculated. A distinct customer count represents something different from a transaction count.

## Interactive Filters
The dashboard includes slicers for:
- Product Name: Focuses the report on a selected product.
- Customer Region: Allows comparison across customer regions.
- Gender: Filters the analysis by the gender categories recorded in the dataset.
These filters make it possible to explore the KPIs and charts from different perspectives without creating separate reports for each category.

## Business Questions Addressed
Sales data can contain useful information about revenue, profitability, product performance, and customer behaviour. However, these details are more difficult to interpret when they are not presented in a clear and organised format.
A business may generate substantial revenue without having a clear understanding of its profit performance, the costs associated with sales, or the product and customer segments contributing to its results.
This project addresses that challenge by using Power BI to organise key sales metrics and present them through an interactive dashboard.
The dashboard was designed to help explore the following questions:
1. What are the overall revenue, profit, cost of goods sold, and profit margin?
2. How does profit vary across product brands?
3. How is cost of goods sold distributed across product colours?
4. How does recorded profit vary across customer income levels?
5. How does revenue change from month to month?
6. How does the customer metric change over time?
7. How do the results differ when filtering by product name, customer region, or gender?
These questions connect the dashboard's visuals to practical business reporting needs.

## Business Insights
- Profitability: The business generated ₦465.67M in profit from ₦2.33B in revenue, giving an overall profit margin of approximately 20%.
- Top-performing product: Laptop A13 generated ₦105.3M in profit, contributing about 23% of total profit. This makes it an important product to monitor when making inventory and sales decisions.
- Profit concentration: Laptop A13, Sofa Classic, and Desktop PC D21 together contributed 52% of total profit. The business should understand what drives their performance while monitoring the profitability of other products.
- Sales performance: Peter generated ₦434.8M in revenue, accounting for approximately 19% of the six sales representatives' combined revenue. Comparing sales approaches across the team could help identify opportunities to improve performance.
- Regional cost differences: Lagos recorded the highest cost of goods sold at ₦493.8M, approximately 17% higher than Abuja, which recorded the lowest. Further analysis could help explain the difference in sales volume, product mix, and purchasing costs.
- Customer activity: Monthly customer counts remained relatively stable from January to April, ranging from 499 to 536, with April recording the highest count. May contains only 18 records, so it should not be compared directly with the preceding months.

## Recommendations
- Monitor the profitability and availability of leading products.
- Investigate the factors contributing to the high profit concentration among the top three products.
- Review regional cost differences to identify potential cost-saving opportunities.
- Compare sales representative performance alongside revenue, profit, and customer activity.
- Continue monitoring customer trends as more complete monthly data becomes available.
  
## Conclusion
This project demonstrates how I used Power BI to organise sales information into an interactive dashboard focused on revenue, profitability, costs, products, customers, and monthly trends.
The work brings together the analytical stages behind a report—from understanding and preparing the data to reviewing the model, developing measures, and presenting results through visualisations.
My focus was not simply to display numbers, but to make the information easier to explore and connect the visuals to questions a business might need to investigate.

