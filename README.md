### Project Title

Awesome Chocolate Factory: Sales & Performance Dashboard

### Brief One Line Summary

An end-to-end Azure SQL + Power BI BI project that cleans, models, and visualizes sales data using a Star Schema and advanced DAX calculations.

### Overview
This project demonstrates a complete business intelligence workflow for the Awesome Chocolate Factory using Azure SQL Database and Power BI. Raw sales data is stored and structured in Azure SQL, transformed and modeled in Power BI using a Star Schema, and analyzed through advanced DAX measures such as Year-on-Year (YoY) profit. The final output is a fully interactive dashboard that provides stakeholders with clear insights into sales, shipping, and profitability performance.
<img width="1168" height="655" alt="image" src="https://github.com/user-attachments/assets/96304d1c-93b4-4eed-a39c-9c99b29ac6a6" />


### Problem Statement

The management team at the Awesome Chocolate Factory required a centralized, interactive analytics solution to track sales, shipping, and profitability KPIs. Data was previously fragmented and difficult to analyze at scale. This project addresses the challenge by building a cloud-backed BI dashboard that enables timely, data-driven decision-making.

### Dataset

The project uses three core datasets:
Shipments (Fact table)
Dimension Data (Product, Customer, Geography)
Calendar (Date dimension)
The data is stored in Azure SQL Database and modeled in Power BI using a Star Schema. Sample CSV files are included in the repository for reference and reproducibility.

### Tools and Technologies

Azure SQL Database (Cloud data storage and querying)
Power BI (Power Query, Data Modeling, DAX, Visualization)
Excel (Original data source)

### Methods

Data Ingestion & Storage: Loaded structured sales data into Azure SQL Database to simulate a production-grade analytics backend.
Data Cleaning & Transformation: Used Power Query to clean data, handle missing values, and create derived columns.
Data Modeling: Designed and implemented a Star Schema, defining relationships between fact and dimension tables for performance and scalability.
Advanced DAX Calculations: Authored optimized DAX measures, including YoY profit growth, margin analysis, and KPI metrics.
Interactive Report Development: Built a multi-page Power BI dashboard using KPI cards, line charts, donut charts, treemaps, slicers, tooltips, and conditional formatting.
Testing & Validation: Validated relationships, filters, and DAX logic to ensure accurate insights and smooth user interactions.

### Key Insights

A Star Schema combined with Azure SQL significantly improves scalability and performance in BI solutions.
DAX time-intelligence functions enable advanced business insights beyond basic aggregations.
Well-designed dashboards balance analytical depth with intuitive UX to maximize business adoption.

### Dashboard/Model/Output

A complete Power BI (.pbix) file containing the full solution.
A dynamic Sales & Performance Dashboard backed by Azure SQL.
Visual insights including profit by country, YoY growth trends, and product-level performance.
    

### How to Run This Project?

Install Microsoft Power BI Desktop.
Download the .pbix file from this repository.
(Optional) Restore or connect to the Azure SQL Database using the provided schema and credentials.
Open the file in Power BI Desktop to explore the dashboard interactively.

### Results & Conclusion
This project delivers a cloud-backed, end-to-end BI solution for the Awesome Chocolate Factory. By integrating Azure SQL Database with Power BI, the dashboard provides a scalable, professional-grade analytics platform that enables management to monitor KPIs, identify trends, and make informed business decisions.
