📊 **Project Overview**

This project, developed through the Maven Analytics Guided Project series (https://mavenanalytics.io/data-playground/global-electronics-retailer), demonstrates a full-scale Business Intelligence workflow. 
The objective was to transform raw, fragmented data (CSV and PDF) into a relational data model capable of delivering deep analytical insights.

The project covers the entire BI stack:

ETL (Extract, Transform, Load): Connecting to flat files and cleaning data using Power Query.

Data Modeling: Designing a Star Schema in Power Pivot with optimized table relationships.

Calculated Measures: Authoring complex logic using DAX to track performance over time.

🛠️ **Technical Challenge & Solution**

*Date Locale Resolution*

During the data ingestion phase, I encountered an issue where date formats were not aligning with my local system settings (non-US).

The Problem: Standard "Change Type" steps caused errors or incorrect date-swapping for US-formatted (MM/DD/YYYY) data.

The Solution: I implemented a fix by utilizing Power Query’s "Regionale" setting. By explicitly defining the source as English (United States), I ensured data integrity and prevented errors in downstream Time Intelligence calculations.

📈 **Key DAX Measures**

To drive the dashboard's analytics, several measures focused on sales performance and historical comparisons

1. Order Quantity = DISTINCTCOUNT(Sales[Order Number])
2. Total Revenue = SUMX(Sales, [Quantity]*RELATED(Products[Unit Price USD]))

📈 **PivotCharts**
<img width="885" height="636" alt="image" src="https://github.com/user-attachments/assets/de44cde4-c59a-44ac-809d-d0372f99c28c" />

Finally, the use of Pivot Charts and slicers were added to design a simple interactive report that the sales managers can use to analyze revenue trends and product category performance.
