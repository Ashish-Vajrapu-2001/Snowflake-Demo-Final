# Myntra CLV Analytics - Silver Layer

This dbt project transforms raw Bronze data (ingested via Fivetran) into the Silver layer.

## Architecture
*   **Source:** Snowflake Database `BRONZE` (Fivetran managed)
*   **Target:** Snowflake Database `SILVER`
*   **Orchestration:** Fivetran Webhook -> dbt Core

## Models
*   **Staging (SCD Type 1):** 11 incremental models (ERP, CRM, Marketing)
*   **Snapshots (SCD Type 2):** 2 snapshots (Customers, Items)

## Quick Start