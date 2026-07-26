E-Commerce Conversion Funnel and Customer Retention Analysis
Turning raw website event logs into actionable business metrics using Google Sheets.

Analyzed raw e-commerce website activity logs in Google Sheets to evaluate customer behavior across the product-view, shopping-cart, and purchase journey. Built a conversion funnel using unique-user metrics, prepared transaction-level data for cohort analysis, and calculated monthly customer retention rates. The project demonstrates advanced spreadsheet modeling, pivot tables, lookup functions, data preparation, funnel analysis, cohort analysis, and executive-level communication.


ecommerce-business-analytics.xlsx
https://docs.google.com/spreadsheets/d/1bmhr4IGUzAr3PbWkQtJZLq-msx3rLTdmxWBTP8KA7pM/edit?usp=sharing

Images
executive-summary.png
conversion-funnel.png
retention-rates.png
cohort-analysis.png
data-preparation.png

Documentation/
E-Commerce Business Analytics Portfolio Project.pdf


Project Overview

This business analytics project examines how customers interact with an e-commerce website and how effectively the website converts product interest into completed purchases.

Using raw website event logs, I developed a three-stage conversion funnel, prepared purchase data for cohort analysis, and calculated monthly customer retention rates. The analysis transforms transaction-level activity into business metrics that an executive team can use to evaluate customer acquisition, conversion performance, and repeat purchasing behavior.

Business Objective

The analysis was designed to answer two primary business questions:

How effectively does the website convert product-page visitors into customers?
How consistently do customers return and make additional purchases after their first purchase?
Dataset

The dataset contains customer activity recorded from an e-commerce website.

Each row represents an individual user event and includes:

user_id: Unique customer identifier
event_type: Website activity performed by the customer
category_code: Product category
brand: Product manufacturer or brand
price: Product price in U.S. dollars
event_date: Date of the customer activity

The recorded event types represent three stages of the customer journey:

Product page view
Shopping cart activity
Purchase
Tools and Techniques

Tool: Google Sheets

Techniques applied:

Data filtering and validation
Pivot tables
Unique-user calculations
Conversion-funnel analysis
Customer cohort analysis
Monthly retention analysis
VLOOKUP
TEXT
DATEDIF
Fixed and relative cell references
Spreadsheet organization and documentation
Executive summary development
Analysis Process
1. Conversion Funnel

I created a three-stage conversion funnel to measure customer progression from product-page views to shopping-cart activity and completed purchases.

The funnel was calculated using unique customer counts rather than total event counts. This prevented customers with multiple activities from being counted repeatedly within the same stage.

I calculated:

Overall conversion from initial product view to purchase
Conversion between each consecutive funnel stage
Customer drop-off between stages
2. Purchase Data Preparation

I isolated completed purchase events from the complete activity log and created a dedicated purchase dataset.

For every purchasing customer, I calculated:

First purchase date
Month of each purchase
Month of the first purchase
Number of months since the first purchase

This prepared the dataset for customer cohort and retention analysis.

3. Cohort Analysis

Customers were organized into acquisition cohorts according to the month of their first purchase.

For each cohort, I measured the number of unique customers who returned and completed another purchase during the following months.

The analysis tracked customer activity from cohort age zero through cohort age four.

4. Retention Analysis

Monthly retention rates were calculated by comparing the number of returning customers with the original number of customers in each acquisition cohort.

This analysis helped identify:

Differences in retention between acquisition cohorts
Changes in repeat-purchase behavior over time
Months in which customer engagement declined
Opportunities for customer re-engagement initiatives

Key Findings
Conversion performance: The September 2020 cohort had the strongest retention, with 6.25% of users returning in month 1 and a small re-engagement in month 4 (3.13%).

Largest customer drop-off: [Insert the stage with the greatest decline.]
Customer retention: Most recent cohorts (December 2020 to February 2021) exhibit very low or zero retention beyond the first month.
Cohort pattern: Subsequent cohorts show a downward trend: the October 2020 cohort retained 4.81% in month 1 but declined to 0% by month 4.

Business Recommendations

Based on the completed analysis, the company should consider:

Investigating the customer journey stage with the greatest user drop-off
Testing improvements to shopping-cart and checkout experiences
Creating follow-up campaigns for first-time purchasers
Comparing acquisition sources for high-retention and low-retention cohorts
Monitoring funnel conversion and cohort retention as recurring performance indicators
Project Deliverables
Three-stage conversion funnel
Monthly acquisition cohorts
Customer retention matrix
Prepared purchase-level dataset
Executive summary
Documented spreadsheet workbook

View the Project

Interactive Google Sheets project:
Open the completed spreadsheet with the link in the top.

Project Preview

Conversion Funnel
Customer Retention
Cohort Analysis
Skills Demonstrated

Execl Google · Sheets · Business Analytics · Conversion Funnel · Cohort Analysis · Customer Retention · Pivot Tables · Data Preparation · Data Validation · Executive Reporting
