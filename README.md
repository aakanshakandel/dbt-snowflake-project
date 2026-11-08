# dbt-snowflake-project
# Project Overview – AWS, Snowflake and dbt Data Pipeline

This project involved building an end-to-end data engineering pipeline using AWS, Snowflake and dbt to transform raw data into structured, analysis-ready datasets.

I started by transferring raw data stored in **Amazon S3 into Snowflake**, using Snowflake's data-loading capabilities to ingest the data into database tables. This allowed me to work with the data in a cloud-based data warehouse, where I could explore its structure and perform SQL queries.

I then integrated **dbt (data build tool) with Snowflake** to develop the data transformation workflow. Using SQL-based dbt models, I transformed the raw data into cleaner, more structured datasets. This involved organising the transformations into models using the medallion structure, defining relationships between datasets and preparing the data for further analysis.

The project helped me understand how cloud storage, data warehousing and transformation tools work together in a modern data engineering environment. I also prepared and delivered a presentation to my team at FDM Group, explaining the architecture, implementation process and technologies used, following my manager's encouragement to share my independent learning.

**Technologies Used:** AWS S3, Snowflake, dbt, SQL
