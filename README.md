
# DAC Stores Sales Performance Analysis | Power BI Dashboard

## Project Overview

This project presents an interactive sales performance dashboard developed using Microsoft Power BI to analyse DAC Stores' business performance.

The analysis focuses on product sales, profitability, sales trends, promotional discounts, customer activity, and geographic sales distribution.

The objective is to transform transactional sales data into meaningful business intelligence that supports better decisions in inventory management, marketing, profitability, and business growth.

## Business Problem

Retail businesses generate large volumes of transactional data, but without effective analysis, identifying profitable products, understanding customer purchasing patterns, and evaluating sales performance can be challenging.

DAC Stores needs visibility into several important business questions:

1. Which five products generate the highest and lowest sales?
2. Which products contribute the most and least profit?
3. Which products sell the highest and lowest quantities?
4. How does sales performance change over time?
5. What is the relationship between total sales and profit?
6. Which promotional campaigns account for the greatest discounts?
7. How are sales distributed across different cities?
8. How can these findings improve business decision-making?

## Project Objectives

- Evaluate product performance using net sales, profit, and units sold.
- Identify top-performing and underperforming products.
- Analyse sales trends across different time periods.
- Examine the relationship between revenue and profitability.
- Assess promotional discount distribution.
- Explore geographical sales performance.
- Develop an interactive dashboard for business performance monitoring.

## Tools and Technologies

**Microsoft Power BI:** Dashboard development, data modelling, interactive visualisations, and reporting.

**Power Query:** Data preparation and transformation environment.

**DAX:** Power BI's calculation language for analytical measures and aggregations.

**Data Modelling:** Organisation of transactional and dimension tables for analysis.

## Dataset Overview

The Power BI model references a central fact table and supporting dimension tables.

### Fact Table

The fact table contains fields used in sales analysis, including:

- Order ID
- Customer ID
- Transaction Date
- Total Sales
- Net Sales
- Profit
- Units Sold
- Discount Value

### Dimension Tables

**Dim Product:** Product Name

**Dim Promotion:** Promotion Name

**Dim Customers:** City

These tables support analysis across products, promotions, and customer locations.

## Dashboard 1: Top and Bottom Five Products

This dashboard compares product performance using three key business metrics:

### 1. Net Sales Analysis

The top-five and bottom-five net sales visualisations are designed to identify products contributing the most and least to sales revenue.

**Business insight:** Products generating strong net sales may represent important revenue drivers. Products with consistently low sales may require further investigation into pricing, demand, availability, or marketing effectiveness.

**Recommendation:** Prioritise inventory availability for products with proven demand while investigating why lower-performing products are struggling.

### 2. Profitability Analysis

The profit comparison examines product contributions to overall business profitability.

**Business insight:** High revenue does not automatically translate into high profit. Comparing sales rankings with profit rankings can reveal differences in product economics.

**Recommendation:** Evaluate product profit margins alongside total profit before making pricing, promotion, and inventory decisions.

### 3. Units Sold Analysis

This section compares products according to their total sales quantities.

**Business insight:** Products selling in high quantities may be important demand drivers, even when their contribution to revenue or profit is comparatively smaller.

**Recommendation:** Compare units sold with revenue and profit to distinguish high-demand products from high-value products.

### Interactive Filtering

Users can explore product performance using filters for product name, promotion name, transaction date, and customer ID.

## Dashboard 2: Market Survey

### 4. Sales Trend Analysis

The line chart presents total sales over time using a date hierarchy.

**Business insight:** Analysing sales over different periods helps stakeholders identify performance fluctuations, possible seasonal patterns, and changes in demand.

**Recommendation:** Use historical trends to inform inventory planning, sales targets, and marketing schedules.

### 5. Sales and Profit Relationship

The scatter chart compares total sales and profit.

**Business insight:** The visual supports investigation into whether increased sales correspond with increased profitability.

**Recommendation:** Evaluate the relationship using an appropriate level of detail, such as products, customers, or transactions, to identify segments with stronger or weaker profitability.

### 6. Promotional Discount Analysis

The promotional chart compares discount values across different promotions.

**Business insight:** Promotions differ in the total discounts they generate. Higher discount expenditure does not necessarily indicate better promotional effectiveness.

**Recommendation:** Combine discount values with incremental sales, gross profit, and promotional costs to assess campaign returns.

### 7. Geographic Sales Analysis

The geographic map displays total sales by customer city.

**Business insight:** Understanding the geographic distribution of sales can help identify established markets, geographic concentration, and locations requiring additional investigation.

**Recommendation:** Compare city-level sales with customer counts, order frequency, and profitability before prioritising expansion.

### 8. Order Activity

The dashboard includes an Order ID summary card.

**Business insight:** An accurate order count helps stakeholders assess transaction volume and monitor business activity.

**Recommendation:** Validate the aggregation to ensure that the card reports the intended number of orders, preferably using a distinct count where appropriate.

## Strategic Business Recommendations

Based on the analytical scope of the dashboards, the following actions are recommended:

**1. Improve inventory allocation**

Use product demand, sales contribution, and profitability together to determine which products deserve greater stock investment.

**2. Prioritise profitable growth**

Avoid evaluating performance using revenue alone. Include product margins and operating costs in business decisions.

**3. Optimise promotional spending**

Assess whether the sales and profit generated by each promotion justify its discount costs.

**4. Strengthen geographic planning**

Use city-level performance to identify markets for customer acquisition, retention, and potential expansion.

**5. Improve demand forecasting**

Analyse sales trends across multiple periods to support more accurate purchasing and resource allocation.

**6. Develop performance monitoring**

Track sales, profitability, units sold, order count, and discount expenditure through consistently defined KPIs.

## Dashboard Features

- Two-page interactive Power BI report.
- Top-five and bottom-five product rankings.
- Sales and profitability comparisons.
- Product quantity analysis.
- Time-based sales trend visualisation.
- Promotional discount analysis.
- Geographic sales mapping.
- Interactive slicers for detailed exploration.

## Skills Demonstrated

- Business intelligence reporting
- Data visualisation
- Sales performance analysis
- Product performance evaluation
- Data modelling
- Business KPI analysis
- Analytical problem-solving
- Data storytelling
- Business decision support


## Conclusion

The DAC Stores Sales Performance Dashboard demonstrates how Power BI can be used to organise retail transaction data into an interactive business intelligence report.

By combining product rankings, sales trends, profitability analysis, promotional activity, and geographic performance, the project provides a foundation for understanding business performance and identifying opportunities for improvement.

The project highlights the importance of evaluating sales volume, revenue, and profit together rather than relying on a single metric.


