# Airbyte-dbt-PowerBI-Airflow
Data Engineering Project

🏗️ Project Architecture

Ingestion (Airbyte)

Pulls data from sources (e.g., Stripe, Shopify, MySQL, CSVs, APIs).

Loads into your warehouse (Postgres, Snowflake, BigQuery, Redshift).

Transformation (dbt)

Cleans raw data (staging models).

Builds business logic (intermediate models).

Creates analytics-ready tables (fact & dimension models).

Adds data tests + documentation.

Visualization (Power BI)

Connects to the transformed tables (fct_sales, dim_customers, etc.).

Dashboards for KPIs (Revenue, Retention, Customer Lifetime Value).

Orchestration (Airflow)

Schedules & monitors pipelines.

Example DAG:

Run Airbyte sync

Run dbt transformations

Notify Power BI refresh
