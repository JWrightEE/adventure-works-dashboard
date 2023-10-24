# AdventureWorks Dashboard

![Dashboard Gif](gifs/AdventureWorksGif.mp4)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Design](#design)
- [Dashboard](#dashboard)
  - [Executive Summary View](#executive-summary-view)
  - [Map View](#map-view)
  - [Product Detail View](#product-detail-view)
  - [Customer Detail View](#customer-detail-view)
  - [Custom Additions](#custom-additions)
- [Insights](#insights)

## Introduction

The goal of this project was to create a business intelligence dashboard for AdventureWorks, a fictional cycling equipment company, using Power BI. The purpose for doing this was to demonstrate my ability
to build insightful, accurate, and aesthetic reports in Power BI.

The dataset was supplied by Maven Analytics during their [Power BI Desktop for Business Intelligence course](https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop) and is available from Microsoft.

## Features

- Analyze product level trends
- Track key performance indicators (KPIs) related to revenue, sales, returns, and profit
- Compare sales performance across different regions
- Create aesthetic and insightful pages directed at a specific target audience (exec vs manager vs analyst)
- Identify high-value customers
- Utilize latest AI visuals such as decomposition tree and anomaly detection to improve data insights and reduce errors
- Provide dense layers of analysis while maintaining a simple overall presentation for executive level end-users

## Design

1. Connect and transform raw data
2. Build a relational data model
3. Create calculations and measures using DAX
4. Design an interactive and dynamic dashboard

## Dashboard

### Executive Summary View

- High-level KPI tracking for revenue, profit, orders, and return rates
- Target KPIs for month-to-month performance vs expectations
- Top products performance with regard to category
- page level filtering for detailed analysis
- drill-through feature to populate product detail view

### Map View

- Scaled map view of total orders by location
- Slicer for quick filters by region

### Product Detail View

- detailed, per-product performance created by drill-through
- Price adjustment metric for performing "what-if" analysis
- Product metric for trending specific product data such as orders, revenue, profit, returns, and return %

### Customer Detail View

- Overall customer and per-customer analysis

### Custom Additions

- Custom tooltip UI for on-demand metrics
- popup filter pane for year and geography
- sidebar navigation for improved user-experience

## Insights

 - Approximately $24.9 million in revenue was generated between January 2020 and June 2022, generating $10.5 million in profit.
 - Accessories account for the largest number of orders, specifically with tires and tubes being the most ordered product type. However, a large percentage of the total profit comes from bike sales which account for roughly $9.7 million, or roughly 92.3% of the total profit.
 - Clothing has the highest return rate of all order categories, with shorts being the most returned item. However, an outlier in returns rates is the Road - 750 Black, 48 bike, which has a return rate of 4.23% which is significantly higher than other bikes. This would be worth investigating as a possible manufacturer defect associated with this bike that responsible for the higher than normal return rate.
 - The highest percentage of order originate from the United States. However, surprisingly the Australian market is very large, accounting for roughly 6,000 orders whereas all of Europe (UK, Germany, and France) account for 7,380 order combined.
 - Customer growth was fairly flat from January 2020 to July 2021 where is suddenly increased by almost 350 %. This could be attributed to a sale if it were only seen over one month, but seeing as that new customer number is maintained in proceed months, it's more likely that the spike in customer growth coincided with an event such as a new location opening.
 - While unique customer numbers have increased over this period of time, revenue per customer has been on a steady decline. This could be explained by several factors such as increased inflation as well has post-Covid manufacturing costs going up or product availability being less due to production constraints.
 - The largest spikes in revenue come in the month of December each year, with an average increase of 158 % over the previous month. This is likely due to the Christmas holiday.

