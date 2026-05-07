# Retail Sales Data Warehouse – ETL & Data Quality Validation

## Project Overview

This project implements an end-to-end Retail Sales Data Warehouse using Databricks and SQL with Medallion Architecture (Bronze, Silver, and Gold layers).

The project includes:
- ETL pipeline implementation
- Data cleaning and transformation
- SCD Type 2 implementation
- Data quality validation
- Fact and dimension table creation
- Business analytics queries
- Incremental load handling
- Archival validation

## Tech Stack

- Databricks
- SQL
- AWS S3
- GitHub
- Delta Tables

## Project Structure

retail-sales-dwh/

├── Project Setup

├── Archive

├── Bronze

├── Silver
│ ├── Silver Layer
│ └── Data Quality Checks

├── Gold
│ ├── Gold Layer
│ ├── Validation Checks
│ └── Business Analytics

└── README.md

## Schemas Created

- retail_dwh.bronze
- retail_dwh.silver
- retail_dwh.gold
- retail_dwh.archive

## Source Files

- customers_src.csv
- products_src.csv
- stores_src.csv
- sales_transactions_src.csv

## Silver Layer

Performed:
- Data cleaning and transformations
- Duplicate removal
- Email standardization
- Data validation checks
- Date standardization
- Referential integrity validation

## Gold Layer

Implemented:
- DimCustomer (SCD Type 2)
- DimProduct
- DimStore
- FactSales

Performed:
- SCD Type 2 validations
- Fact table validations
- Referential integrity checks
- Business analytics queries

## Business Analytics

Created analytical queries for:
- Revenue analysis
- Customer analysis
- Product analysis
- Store and region analysis
- Monthly sales trends
- Top customers and products

