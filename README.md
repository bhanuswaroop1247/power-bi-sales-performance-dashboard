### Project Title

Awesome Chocolate Factory: Sales & Performance Dashboard

### Brief One Line Summary

An end-to-end BI project for the Awesome Chocolate Factory, using Power BI to clean, model, and visualize sales data with advanced DAX calculations.

### Overview

This project showcases a complete business intelligence workflow within Power BI for the Awesome Chocolate Factory. It starts with data cleaning in Power Query, proceeds to building a relational data model (Star Schema), and involves writing complex DAX measures to derive key metrics like Year-on-Year profit. The final result is a fully interactive dashboard designed to give stakeholders a clear view of sales and shipping performance.

### Problem Statement

The management team at the Awesome Chocolate Factory needed a unified, interactive tool to track sales, shipping, and profitability KPIs. Without a centralized dashboard, it was difficult to analyze performance trends and make timely, data-driven decisions. This project solves that problem by creating a comprehensive Power BI report that provides clear, actionable insights.

### Dataset

The project utilizes three core data files from the Awesome Chocolate Factory: `Shipments.csv`, `Dimension Data.csv`, and `Calendar.csv`. These files are structured to build a Star Schema data model within Power BI and are included in the repository.

### Tools and Technologies

* **Power BI** (including **Power Query** and **DAX**)
* **Excel** (Original Data Source)

### Methods

* **Data Cleaning and Transformation:** Utilized **Power Query** to clean raw data, handle missing values, and create additional columns to prepare the dataset for analysis.
* **Data Modeling:** Designed and implemented a **Star Schema** data model, creating relationships between fact and dimension tables to ensure data integrity and optimize query performance.
* **Advanced DAX Calculations:** Authored complex **DAX** (Data Analysis Expressions) measures from scratch to calculate key business metrics, including dynamic **Year-on-Year (YoY) profit growth**.
* **Interactive Report Development:** Built a multi-page, interactive report featuring a range of visualizations (KPI cards, line charts, donut charts, treemaps) and user-centric features like **slicers, custom tooltips, and conditional formatting**.
* **Testing and Validation:** Conducted thorough testing of the report's interactions, filters, and DAX calculations to ensure accuracy and a seamless user experience.

### Key Insights

* A well-designed Star Schema is fundamental for performance and scalability in Power BI.
* DAX enables complex business logic and time-intelligence calculations that go far beyond simple aggregations.
* Effective report design combines powerful analytics with an intuitive user interface to drive adoption and business value.

### Dashboard/Model/Output

* A complete Power BI file (`.pbix`) containing the full solution.
* A dynamic Sales & Performance dashboard for the Awesome Chocolate Factory.
* Visualizations showing profit by country, YoY growth trends, and product performance.
    

### How to Run This Project?

To view and interact with the project, you will need Microsoft Power BI Desktop. The `.pbix` file can be downloaded from this repository and opened directly in the application.

### Results & Conclusion

* The project delivered a comprehensive BI solution providing the Awesome Chocolate Factory with an interactive view of their sales performance.
* The dashboard successfully visualizes key KPIs, enabling data-driven decision-making for management.
* This project is a practical, end-to-end demonstration of building a professional-grade report in Power BI.
