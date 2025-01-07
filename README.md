# Data-Analysis-using-Pyspark

This project on Tutor Performance analysis using Microsoft Fabric involves several key steps in data engineering and analysis. Here's an overview of how I structured the project and the main tasks involved, broken down by steps.

1. Reading Data from Lakehouse

Objective: Ingest raw data stored in the Lakehouse.
Using Tools/Frameworks: PySpark.
Data Sources:  CSV format.

3. Data Cleaning

Objective: Clean and preprocess the data, including handling nulls, duplicates, and incorrect data types.
Common Tasks:
Handle missing values.
Remove duplicates.
Format date and timestamp fields.
Validate data types.

3. Aggregation and Grouping
Objective: Aggregate performance data to generate meaningful insights.

4.ETL (Extract, Transform, Load) Process
Objective: Perform the ETL to extract data, 
ETL Tasks:
Extract data from tables.
Transform data using filtering, aggregations, or joins.
Load cleaned and transformed data to the dimension and fact tables.

5.Joining Dimension and Fact Tables
Joined tutor performance fact data with dimension tables (e.g., tutor, program, intake,comments table) for detailed information.
