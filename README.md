## Supply Chain Inventory Analytics Hub -PowerBi Dashboard

## Project Overview

This Power BI dashboard provides a comprehensive an_alytical view of inventory performance, designed to help inventory managers, supply chain analysts, and business stakeholders make data-driven decisions. It focuses on optimizing stock levels, improving turnover, identifying critical SKUs, and ensuring timely reordering to minimize costs and prevent stockouts.

## Dashboard Pages & Key Features

The dashboard is organized into key analytical views:

## Preview 
Page 1
![2025-05-31T10_02_51 969Z](https://github.com/user-attachments/assets/74dcf3f7-0c9f-448d-b61f-0dc5c914ce1e)

Page 2
![025-05-31T10_03_18 025Z](https://github.com/user-attachments/assets/06ecc33a-9ea6-46e6-8dea-50ec214a78a2)

### Page 1: ABC Analysis & Re-order Overview

*   **Sum of Annual Revenue and Count of SKU ID by ABC Category:**
    *   Visualizes the Pareto principle in inventory, highlighting high-value (A), medium-value (B), and low-value (C) SKUs based on their annual revenue contribution.
    *   Compares revenue contribution with the sheer count of SKUs in each category.
*   **Count of Items Requiring Re-ordering:**
    *   A key performance indicator (KPI) card showing the total number of SKUs that have fallen below their re-order point or safety stock and require immediate attention.

### Page 2: Detailed Inventory Performance

*   **Top-Level KPIs:**
    *   **Current Value in Warehouse (WH):** Total monetary value of current inventory holdings (e.g., ₹77.33M).
    *   **Number of SKUs:** Total distinct stock-keeping units managed.
    *   **Inventory Turnover Ratio:** Measures how many times inventory is sold or used over a period (e.g., 5.42).
*   **Distribution Analysis (by ABC Category):**
    *   **Distribution of Annual Revenue:** Breaks down revenue contribution further within ABC categories (potentially by sub-segments like X, Y, Z).
    *   **Distribution of Current Stock:** Shows stock quantity or value distribution across ABC categories.
    *   **Distribution of ABC:** An aggregated view of value or quantity within ABC ranks.
    *   **Distribution of Inventory Turnover Ratio:** Compares turnover rates across different ABC segments.
*   **SKUs to Re-order & Stock Status:**
    *   **Card:** Highlights the number of SKUs needing re-ordering.
    *   **Donut Chart (Stock Status):** Visually represents the proportion of SKUs that are "Below Safety Stock," "In Stock," or "Out of Stock."
*   **Sum of Sales Amount by Week Date:**
    *   A line chart tracking sales trends over time, helping to understand demand patterns.
*   **Detailed SKU Table:**
    *   Provides granular information for each SKU, including:
        *   SKU ID
        *   Current Stock
        *   Average Lead Time (days)
        *   Re-Order Point
        *   Safety Stock
        *   Stock Status (e.g., In Stock, Out of Stock, Below Re-order Point)

## Data Sources (Assumed)

*   Sales Transaction Data
*   Inventory Master Data (SKU details, lead times, costs)
*   Current Stock Level Data (from WMS or ERP)
*   Past Order Data

## Key Metrics & Calculations

*   Annual Revenue per SKU
*   ABC Classification (e.g., A: top 80% revenue, B: next 15%, C: last 5%)
*   Inventory Value (Current Stock * Unit Cost)
*   Inventory Turnover Ratio (Cost of Goods Sold / Average Inventory)
*   Re-Order Point (ROP)
*   Safety Stock
*   Stock Status (based on current levels vs. ROP and Safety Stock)

## Tools Used

*   Microsoft Power BI

## Purpose & Business Value

*   **Enhanced Visibility:** Provides a clear view of inventory status, value, and movement.
*   **Optimized Stock Levels:** Helps identify overstocked and understocked items, enabling adjustments to reduce holding costs and prevent stockouts.
*   **Improved Re-ordering:** Highlights SKUs needing re-ordering based on calculated ROPs and safety stock levels.
*   **Strategic Focus:** ABC analysis allows prioritization of management efforts on high-value items.
*   **Data-Driven Decisions:** Empowers managers to make informed decisions regarding procurement, stock allocation, and sales strategies.
*   **Improved Working Capital:** By optimizing inventory, capital tied up in stock can be minimized.

## How to Use

1.  Navigate between `Page 1` and `Page 2` using the tabs at the bottom.
2.  Review KPIs on Page 2 for an overall health check.
3.  Use ABC analysis visuals to understand revenue and stock distribution.
4.  Focus on "SKUs to Re-order" and the detailed SKU table to identify items requiring immediate action.
5.  Analyze sales trends to anticipate future demand.

## Author 
Abhishek Shrimali
---
