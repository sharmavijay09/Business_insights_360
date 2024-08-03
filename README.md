# Business Insights 360

Live Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiNzM4M2MyNWMtZWQ4My00MGE2LWI1NTAtYjQ1Y2E0ODhiZjAxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

## Overview

Business Insights 360 is a data analytics project aimed at enhancing decision-making for AtliQ Hardware, a global seller of computers and accessories. This project uses Power BI to provide actionable insights across finance, sales, marketing, and supply chain operations to help the company outperform its competitors.

## Company Background

AtliQ Hardware is a rapidly growing company that distributes its products through retailers, direct sales, and distributors worldwide. With increasing competition, AtliQ Hardware is investing in data analytics to make informed business decisions.

## Project Goals

The main objectives of this project are to:
- Address stakeholder questions using data-driven insights.
- Provide comprehensive reports in areas such as finance, sales, marketing, and supply chain.

## Tech Stack

- **SQL**: For database management.
- **Power BI Desktop**: For creating interactive reports and dashboards.
- **Excel**: For initial data handling and analysis.
- **DAX Language**: For creating calculated columns and measures in Power BI.
- **DAX Studio**: For optimizing Power BI reports.

## Key Learnings and Techniques

- **Project Initiation**: Define objectives, success criteria, deadlines, and stakeholder expectations.
- **Data Modeling**: Utilize Snowflake modeling to organize data for efficient reporting.
- **Power BI Skills**:
  - Creating calculated columns and measures.
  - Data modeling and visual navigation using bookmarks.
  - Error prevention using functions like DIVIDE.
  - Building date tables with M language.
  - Implementing dynamic titles, KPI indicators, and conditional formatting.
  - Setting up auto-refresh and managing permissions in Power BI Services.

## Business Terms Explained

- **Gross Price**: The initial price before any deductions.
- **Pre/Post-Invoice Deductions**: Adjustments made before/after invoicing.
- **Net Invoice Sale**: Total sale amount after deductions.
- **Gross Margin, Net Sales, Net Profit**: Key financial metrics.
- **COGS (Cost of Goods Sold)**: Direct costs of producing goods.
- **YTD/YTG**: Year-to-Date/Year-to-Go.
- **Channels**: Retailer, Direct, Distributors.

## Project Steps

1. **Kick-off Meeting**: Define project goals and gather requirements.
2. **Data Understanding**: Identify available data, such as customer and product details (dimension tables) and transaction records (fact tables).

## Data Details

- **Dimension Tables**:
  - **dim_customer**: Customer details, platforms (Brick & Mortar, E-commerce), and sales channels.
  - **dim_market**: Market regions and sub-zones.
  - **dim_product**: Product divisions, categories, and variants.

- **Fact Tables**:
  - **fact_forecast_monthly**: Forecasted customer needs to improve satisfaction and reduce costs.
  - **fact_sales_monthly**: Actual sold quantities, similar to the forecast table.

- **Additional Tables**:
  - **freight_cost**: Travel and other market costs.
  - **gross_price**: Product gross prices.
  - **manufacturing_cost**: Product manufacturing costs.
  - **Pre/Post-invoice deductions**: Customer-specific deductions.

## Importing Data

Data is imported from a MySQL database to Power BI using provided credentials.

## Data Model

Data modeling is crucial for report performance. Follow best practices, using the Snowflake method in this project.

## Dashboard Designing
Design visuals based on mockups and create measures as needed.

## Home View
Users can navigate to different pages by clicking buttons:
- **Info**
- **Finance View**
- **Sales View**
- **Marketing View**
- **Supply Chain View**
- **Executive View**
- **Support**

## Project Outcome

This report facilitates data-driven decisions and helps answer many "why" questions.

## How to Contribute

If you have suggestions or improvements for the report, feel free to open an issue or submit a pull request.


