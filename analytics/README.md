Welcome to your new dbt project!
# DBT Analytics Project

Personal project for learning and practicing dbt (data build tool) with DuckDB.

## Tech Stack
- dbt Core
- DuckDB
- Python

## Project Structure
- `models/staging` — raw data cleaning and standardization
- `models/marts` — business logic and aggregations
- `seeds/` — static CSV files
- `tests/` — data quality tests

## How to Run
1. Clone this repository
2. Install dependencies:
   pip install dbt-core dbt-duckdb
3. Run dbt:
   dbt run

## Learning Resources
- [dbt Documentation](https://docs.getdbt.com)
- [dbt DuckDB Adapter](https://github.com/duckdb/dbt-duckdb)
