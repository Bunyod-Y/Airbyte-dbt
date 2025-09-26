# Airbyte-dbt
Data Engineering Project

🏗️ Project Architecture

Ingestion (Airbyte)

Pulls data from sources (e.g., Stripe, Shopify, MySQL, CSVs, APIs).

Loads into your warehouse (Postgres, Snowflake, BigQuery, Redshift).

Transformation (dbt)

Cleans raw data (staging models).

Builds business logic (intermediate models).

Creates analytics-ready tables (fact & dimension models)

