# Power BI PM & CapEx Dashboard

This Power BI dashboard brings together preventive maintenance (PM) activities and capital expenditure (CapEx) data, enabling maintenance teams and finance departments to track spend, equipment assets and maintenance performance in a unified view.

## Overview

This report allows users to explore PM and CapEx data through interactive visuals and dynamic filters. Key features include:

- Maintenance cost and asset spend by equipment, department or site  
- PM work orders and completion rates over time  
- CapEx investment summary, comparisons of planned vs actual spend  
- Heat-map or bar views showing high-investment areas and high-maintenance-cost assets  
- Time filters (year, quarter, month), asset-category filters, site/department filters  

## Report Features

### 1. Asset Spend by Category  
A visual chart comparing CapEx spend across asset categories (e.g., machines, infrastructure, IT systems), helping to identify where major investments are concentrated.

### 2. PM Work Order Trend  
A line or area chart tracking the number of work orders created versus completed over time, showing completion rates and backlog trends.

### 3. Spend Comparison – Maintenance vs Investment  
A dual-axis or combo chart showing PM spend alongside CapEx investment over time, highlighting correlation between maintenance burden and investment levels.

### 4. High-Cost Assets & Hot-Spots  
A table or visual showcasing assets with highest maintenance cost, highest downtime or highest investment; or sites/departments where cost intensity is highest.

### 5. Dashboard Snapshot / KPI View  
KPI cards to show: total PM spend YTD, total CapEx spend YTD, PM spend as % of CapEx, asset downtime hours, maintenance backlog count.

## Insights

- Some asset categories may show disproportionately high PM spend relative to investment, indicating ageing equipment or deferred replacement  
- Sites/departments with low CapEx investment but high maintenance burden may benefit from targeted replacement or upgrade  
- Tracking PM (work orders, completion, downtime) alongside CapEx provides a fuller view of asset-lifecycle cost, not just investment cost  

## Tools & Techniques

- Power BI Desktop – for creating the report, data modelling and visuals  
- DAX – for calculating key metrics (e.g., PM spend per asset, downtime cost, CapEx actual vs planned)  
- Power Query / M – for cleaning, transforming and merging PM, work-order, asset and CapEx datasets  
- CSV / Excel – example source files for demonstration or portfolio use  

## Dashboard Preview

![Maintenance Overview Dashboard](screenshots/maintenance_overview.png)

## Data Notice

All data included in this project is either anonymised or synthetic and used for demonstration / portfolio purposes only. It is not linked to any live production system.

## About

Power BI dashboard enabling integrated view of preventive maintenance and capital expenditure for asset-intensive organisations.

### Topics  
`dashboard` `analytics` `business-intelligence` `data-visualisation` `asset-management` `preventive-maintenance` `capex` `powerbi` `maintenance-analytics`

## License  
MIT License
