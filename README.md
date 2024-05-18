# Business Insights 360

## Project Overview

AtliQ Hardware has been growing rapidly in recent years, and they have decided to implement data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data-driven decisions. 
- [Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiODA5NWEzZTItMDZjOS00MzBkLWFiYTItOTRlODZhYjNjN2ExIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=ReportSection870fd0166929d0c75b45)
-  [Video Presentation](https://www.linkedin.com/feed/update/urn:li:activity:7197652297210871809/)


## Tech stacks

- SQL
- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Project charter file

## Business related terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- Forecast Accuracy
- Net/Abs Error
- COGS - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Company’s background

AltiQ Hardware is a company that has grown rapidly in recent years, and opened business all over the globe. It is a company that manufactures and sells, computer and computer accessories through three mediums/channel

- Retailers
- Direct
- Distributors

Recently the company has faced significant loss by opening a store in Latin America based on surveys, intuition, and some Excel analysis. Also, the company’s competitors have employed an analytics team to perform analysis and make data-driven decisions. So, AltiQ Hardware has decided to invest in an analytics team for data-driven insights and decisions in the future to survive better in the industry. 


### Dataset **Understanding.**

We are pulling data from **2 sources** : MySQL and Excel

We have 2 databases containing the following tables: 
- gdb041:
    - dim_customer
        - **27** distinct markets (ex India, USA, Spain)
        - **75** distinct customers throughout the market
        - **2** types of platforms
            - Brick & Motors - Physical/offline store
            - E-commerce - Online Store (Amazon, Flipkart)
        - Three channels
            - Retailer
            - Direct
            - Distributors
    - dim_market
        - **27** distinct markets (ex India, USA, Spain)
        - 7 sub-zones
        - 4 regions 
    - dim_product
        - Divisions
            - P & A
            - PC
            - N & S
    - fact_forecast_monthly
        - This table is used to forecast the customer’s needs in advance
    - fact_sales_monthly
        - This table contains the sold quantity.
- gdb056
    - freight_cost
    - gross_price
    - manufacturing_cost
    - Pre_invoice_dedutions
    - Post_invoice_deductions

We are importing 3 Excel files as well:
- MarketShare: AtliQ and its competitors market share
- Operational Expenses: Ads & promotions and other expenses percentage per market
- targets: AtliQ's NS, GM, NP target data


## Data Model

We have built a Snowfall data model for this project

![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/018e042f-734b-4d8f-8fce-b19ce666eb21)


## Dashboards

### Home view

![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/dac388a6-342e-4632-b91f-340e8197ebda)

## Finance View

![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/0c33b9af-f31d-4272-a774-3152d1152875)

## Sales View

![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/dd74e4ae-489e-4525-a53c-74f2698143f0)
![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/9577e37a-523b-4164-94d4-f71af43b15d1)


## Marketing View

![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/5fdf7925-58aa-4f5a-b640-e7ec0e58c650)

## Supply chain View

![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/99a36b9d-31cf-4cde-b121-6a426421960a)

## Executive View

![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/f2099ed8-2a30-4da4-b425-2307c0939e2a)


## Key Insights
![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/57c4eb4e-a4c8-45fa-ab20-8fb8c61a1545)
![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/7a2f4c8c-b33e-4570-a079-2f47bcef3520)

## Recommendations
![image](https://github.com/Kanikamittal99/Business_Insights_360/assets/32505627/b9c24053-0ff3-417b-820c-2b0e06203c45)

