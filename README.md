# SQL Data Warehouse Analytics | Database Setup

## Project Overview
This project contains the SQL script used to set up the data warehouse environment for my SQL analytics portfolio. It establishes the database, creates the required schema and tables, and prepares the source data environment for further analysis.

This database serves as the foundation for my Customer Report, Product Report, Exploratory Data Analysis (EDA), and Advanced SQL Analytics projects.

## Project Objectives
- **Create the Database:** Set up the `DataWarehouseAnalytics` database for storing and analyzing data.
- **Create the Schema:** Establish the `gold` schema to organize the analytical tables.
- **Create the Tables:** Set up three tables containing customer, product, and sales transaction data.
- **Prepare Source Data:** Establish the data structure required to perform SQL queries, calculations, and analytical reporting.
- **Support Multiple Analytics Projects:** Provide the underlying data used across my SQL portfolio projects.

## Database Structure

The database consists of three main tables:

### 1. `gold.dim_customers`
Contains customer-related information used for customer analysis, demographic insights, and customer segmentation.

### 2. `gold.dim_products`
Contains product-related information, including product names, categories, subcategories, and costs. This table supports product performance and category analysis.

### 3. `gold.fact_sales`
Contains sales transaction data used to analyze orders, revenue, quantities sold, and purchasing patterns.

## SQL Concepts Used
- Database creation and management
- Schema creation
- Table creation
- Database existence checks
- `CREATE DATABASE`
- `CREATE SCHEMA`
- `CREATE TABLE`
- `DROP DATABASE`
- `TRUNCATE TABLE`

## Role in My SQL Portfolio

This database setup provides the source data for the following projects:

- **Customer Report:** Customer-level metrics, customer segmentation, age groups, and purchasing behavior.
- **Product Report:** Product performance, revenue analysis, and product-level KPIs.
- **Exploratory Data Analysis (EDA):** Exploring customer, product, and sales data to identify patterns and trends.
- **Advanced SQL Analytics:** Monthly and yearly sales analysis, cumulative sales, running totals, product performance comparisons, category contributions, and customer spending segmentation.

## Tools and Technologies
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- SQL

## Important Notes
The setup script includes database recreation and table-truncation operations. These operations can delete existing data, so the script should be executed carefully in an appropriate environment.

## Source and Attribution
This database setup script was sourced from an existing GitHub project and is used as the foundation for my SQL learning and analytics projects.

