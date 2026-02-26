# Silver Layer Deployment Guide

## Prerequisites
*   Python 3.8+
*   dbt-snowflake
*   Git access to `myntra_clv_dbt`
*   Snowflake role `TRANSFORMER_ROLE`
*   Bronze tables populated by Fivetran

## Environment Variables
Set these in your shell or CI/CD environment:
*   `DBT_SNOWFLAKE_ACCOUNT`
*   `DBT_SNOWFLAKE_USER`
*   `DBT_SNOWFLAKE_PASSWORD`
*   `DBT_BRONZE_DB` (Default: BRONZE)
*   `DBT_SILVER_DB` (Default: SILVER)

## Deployment Steps

1.  **Install Dependencies:**