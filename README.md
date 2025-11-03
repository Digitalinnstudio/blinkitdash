# Blinkit Sales & Performance Analysis Dashboard

https://app.powerbi.com/reportEmbed?reportId=3e93454f-30d5-41cd-9210-16066d67a1c5&autoAuth=true&ctid=edd67062-29c1-4a50-8fac-9813dfae8e4b

## Project Overview

This repository contains the files and documentation for an end-to-end business intelligence project focused on analyzing the sales and operational performance of **Blinkit** (an online grocery delivery service, a product of Zomato).

The core deliverable is a dynamic and interactive **Power BI Dashboard** designed to provide a high-level summary and granular insights, allowing business stakeholders to monitor key performance indicators (KPIs), track sales by various dimensions, and make data-driven decisions.

## Key Features of the Dash

The dashboard is built to be highly interactive, allowing users to drill down into the data using a comprehensive filter panel.

* **Dynamic KPI Visualization:** Easily switch between viewing charts based on **Total Sales**, **Average Sales**, **Number of Items**, and **Average Rating** with a single click.
* **Comprehensive Filter Panel:** A dedicated filter panel is available for easy selection and resetting of all applied filters.
* **Tier-Based Analysis:** Analyze performance across different Outlet Location Tiers (Tier 1, Tier 2, Tier 3).
* **Outlet Size Segmentation:** Filter data by Outlet Size (e.g., High, Medium).
* **Item Type Specificity:** Investigate the sales and ratings for specific product categories (e.g., Dairy, Snacks).
* **Interactive Cross-Filtering:** All visuals on the dashboard are configured to interact with each other; selecting a segment on one chart dynamically filters all other visuals on the report page.

## KPIs

The primary KPIs displayed prominently at the top of the dashboard for an instant overview of business health include:

* **Total Sales**
* **Average Sales**
* **Number of Items (Sold)**
* **Average Ratings**

## Tech Stack

| Component | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Data Visualization** | Microsoft Power BI Desktop | Dashboard Design and Report Creation. |
| **Data Preparation** | Power Query (M Language) | Data loading, cleaning, and transformation. |
| **Data Modeling** | Power BI Relationship View | Establishing relationships between tables. |
| **Calculations** | DAX (Data Analysis Expressions) | Creating custom measures and calculated columns for KPIs and insights. |
| **Data Source** | Raw data provided in **Excel Sheet** format. |

## Project Steps & Methodology

The project followed a standard BI development lifecycle (as outlined in the tutorial):

1.  **Business Requirements:** Defining the problem statement and required insights (KPIs, dimensions).
2.  **Data Acquisition:** Connecting to the raw data (Excel).
3.  **Data Walkthrough:** Understanding the raw data structure and size.
4.  **Data Preparation (ETL):** Cleaning, transformation, and ensuring data quality.
5.  **Data Modeling:** Establishing relationships and creating a star/snowflake schema.
6.  **DAX Calculations:** Implementing required measures for the defined KPIs.
7.  **Data Visualization:** Designing and building the interactive dashboard in Power BI.
8.  **Insight Generation:** Providing the final report for business strategy.

