# Myntra CLV Analytics — Bronze Layer Deployment Guide

## Prerequisites
- Snowflake account: {{PLACEHOLDER_SNOWFLAKE_ACCOUNT}}
- Fivetran account with API access enabled
- Azure SQL: DBA access to run Change Tracking enablement on source DBs
- Python 3.8+ with requests and pyyaml libraries

## Deployment Steps

### Step 1 — Snowflake Infrastructure
  Run the setup SQL to create databases, roles, and the Fivetran service user.