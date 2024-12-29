# Uber-Data-Engineering-Project

**Overview**

This project demonstrates an end-to-end data engineering pipeline for analyzing Uber trip data. It leverages tools like DataBricks for ETL (Extract, Transform, Load), and customized to fit specific analytical goals.

**Technologies Used**

DataBricks: For ETL pipeline development.

DBFS: To store and analyze large datasets efficiently.

Pyspark: For scripting and data manipulation.

**Features**

1.**Data Ingestion:**

Imported Uber trip raw data into databricks DBFS for preprocessing.

2.**Data Transformation:**

Cleaned and normalized raw data.

Created dimensional tables (e.g. datetime_dim, rate_code_dim,payment_type_dim,payment_type_dim,pickup_location_dim,dropoff_location_dim).

Built a fact_table for analytics. (e.g. fact_table)

3.**Data Export:**

Exported transformed data into SQL Table for efficient querying.

**Pipeline Architecture**

Extract: Load raw data into Databricks DBFS.

Transform: Apply transformations to generate dimension and fact tables.

Load: Store processed data in SQL Table.

**Project Workflow**

1.**DataBricks**

Apply Transformations to clean the data for the Analytics.

2.**Tables:**

**fact_table:** Consolidated facts like revenue and trip distance.

**Dimension tables**: datetime_dim, rate_code_dim,payment_type_dim,payment_type_dim,pickup_location_dim,dropoff_location_dim.

**Dashboard Metrics for Analytics:**

Summary cards for revenue, record count, and average trip distance.

***Revenue Metrics:** Total revenue from trips.

***Trip Analysis:** Average trip distance and fare amount.

***Geographic Trends:** Pickup and drop-off hotspots visualized on a map.



