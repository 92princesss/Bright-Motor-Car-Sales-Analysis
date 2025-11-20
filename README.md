# Bright-Motor-Car-Sales-Analysis
## Data Analytics Project (BrightLearn)

## Project Overview
This project analyzes the Bright Motors Car Sales Dataset to extract insights for the newly appointed Head of Sales .
The goal is to support strategic decisions related to revenue growth ,dealership expansion ,inventory optimization ,and
 pricing effectiveness.

The analysis explores sales patterns, regional performance ,customer perferences, and profitability trends using SQL ,Power BI , and Excel.

## Objectives
- Identifty top revenue-generating car makes and models
- Understand the relationship between price,mileage ,and year
- Analyze regional sales performance 
- Discover emerging customer purchasing trends 
- Provide actionable recommendations to increase sales and efficiency

  ## Tools & Technologies Used
  - Snowflake (SQL)
  - Power BI
  - Mircosoft Excel
  - Mircosoft PowerPoint
  - Miro
 
    ## Project Files
|File| Description |
|----|-------------|
|BrightMotors_Presentation .pptx|Final presentation|
|cars_sales_queries.sql| SQL script for cleaning ,transformation ,and analysis|
|README.md | Project documention |

## Data Workflow
    ###1. Data Ingestion
    - Converted Raw Excel/CSV into CSV
    - Loaded into Snowflake staging using COPY INTO 
    
## 2.Data Cleaning & Transformation
- Converted price fields to numeric
- Created total_revenue ,profit_margin_pct, performance_tier
- Cleaned date formats
- Group by month ,year ,region

## 3.Analysis 
     Computed:
  - Revenue by make/model
  - Sales by region
  - Price vs mileage trends
  - Monthly price and revenue trends
  - Margin tier distribution

## 4. Visualization
Used Power BI to create :
- Top revenue model chart 
- Regional performance map
- Price vs Mileage Scatter plot
- Monthly revenue line chart

### 5.Reporting 
Insights and recommendations compiled in the final presentation.

## Key Insights Summary 
- Top models contribute significantly to revenue
- Strong regional differences in performance
- Mileage and year strongly influence price
- Margin optimization opportunties exist

## Recommendations
- Increase inventory for high-demand models
- Optimize regional differences in performance
- Adjust pricing or negotiate supplier costs
- Launch targeted promotions in underperforming areas
- Track margins monthly in Power BI

## How to Use This project 
1. Run car_sales_queries.sql in Snowflake
2. Export processed data or connect directly to Power BI
3. Build visuals using provided metrics
4. Present insights using BrightMotors_Presentation.pptx
5. """
- 
    
