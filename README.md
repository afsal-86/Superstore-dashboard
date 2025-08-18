🛒 Superstore Data Analysis

This project demonstrates how Excel and Power BI can be used together to transform raw retail data into meaningful business insights. Using the popular Superstore dataset, the analysis explores sales, profit, discount impact, customer behavior, and shipping performance through interactive dashboards and reports.


---

📑 Project Overview

In today’s competitive retail market, data-driven decision-making is crucial. Superstores generate massive amounts of data daily, but without proper analysis, these records provide little value.

This project focuses on:

Cleaning and preparing data in Excel

Modeling and analyzing data in Power BI

Building interactive dashboards to visualize key business metrics

Applying advanced analytics such as RFM segmentation, cohort analysis, and discount–margin sensitivity



---

⚙️ Tools & Technologies

Excel → Data cleaning, preprocessing, pivot tables

Power BI → Data modeling, DAX measures, interactive dashboards

Power Query → ETL (Extract, Transform, Load) pipelines



---

📂 Data Collection & Preprocessing

Source: Public Superstore sales dataset (Excel/CSV format)

Steps Performed:

Removed duplicates & irrelevant fields

Standardized categories (Consumer, Corporate, Home Office)

Created derived metrics (Profit %, Delivery Lead Time, Discount Bands, RFM scores)

Built star schema model: FactSales + Dimension tables (Customer, Product, Date, Region, Ship)

Validated totals, handled missing values, and ensured business rule consistency




---

🔎 Methodology

1. Requirement Gathering – Identified stakeholder needs (KPIs, retention, discount impact)


2. ETL – Cleaned data in Excel & Power Query


3. Modeling – Designed star schema with Fact & Dimension tables


4. Analysis –

Descriptive: Sales, profit, regional trends

Diagnostic: Discount–profit scatterplots, product profitability

Segmentation: RFM scoring, cohort retention analysis

Geospatial: Heatmaps for sales/profit by state/region



5. Visualization – Built Power BI dashboards and Excel reports




---

📊 Results & Insights

Category Performance: Technology had highest sales, Furniture showed profit volatility

Regional Performance: West region was most profitable, South underperformed

Discount Impact: Discounts beyond a certain threshold led to negative margins → Suggested discount cap

Customer Segmentation: A small group of loyal customers contributed disproportionately to revenue

Operational Insights:

Late shipments concentrated in specific regions

Office Supplies had the highest return rates




---

✅ Conclusion

This project highlights how combining Excel and Power BI delivers powerful, actionable insights for retail businesses. By leveraging proper data modeling, advanced analytics, and interactive reporting, businesses can:

Optimize inventory

Improve delivery performance

Increase customer retention

Enhance profitability
