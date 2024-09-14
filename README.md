# Banking System ETL 

## Overview
This project demonstrates the use of **SQL Server Integration Services (SSIS)** to build an ETL (Extract, Transform, Load) pipeline for a banking system. The goal is to extract data from various banking data sources, transform it to meet business requirements, and load it into a data warehouse for reporting and analysis.

## Objectives
- **Data Consolidation**: Extract customer, transaction, loan, and other relevant data from multiple banking systems.
- **Transformation**: Ensure data consistency and accuracy by applying business logic and reformatting the data.
- **Data Warehousing**: Store the transformed data in a **SQL Server** data warehouse for efficient querying and analysis
## Features

### 1. ETL Pipeline with SSIS
- **Extraction**: Retrieves data from multiple sources, such as:
  - Core banking systems for customer data.
  - Transactional systems for daily transactions (deposits, withdrawals, transfers).
  - Loan management systems for tracking loans and repayments.
- **Transformation**:
  - Apply business rules to ensure data uniformity.
  - Clean and deduplicate data.
  - Calculate key metrics (e.g., total loan amounts, interest accruals).
- **Loading**: The transformed data is loaded into a **data warehouse** structured for efficient querying and analysis.

### 2. Centralized Data Warehouse
- **SQL Server-based**: Built on **SQL Server**, leveraging its reliability and scalability.
- **Schema Design**:
  - **Fact tables**: Store transactional data (e.g., transactions, loan disbursements, repayments).
  - **Dimension tables**: Contain descriptive information (e.g., customer demographics, branch details).
- **Query Efficiency**: Optimized for fast querying, supporting business analytics and reporting.


## Technologies Used
- **SSIS (SQL Server Integration Services)**:
  - Manages the complete ETL process, including control flow and data transformations.
- **SQL Server**:
  - Serves as the source and destination for data storage and warehousing.

- **SQL**:
  - Handles data querying, management, and automation using procedures, views, and triggers.

## Use Cases
- **Bank Executives**: Monitor financial performance and identify growth opportunities.
- **Branch Managers**: Track branch performance and customer activity.
- **Loan Officers**: Review loan portfolios and delinquency rates.
- **Customer Analytics Teams**: Analyze customer behaviors and product usage for personalized marketing.

This project provides a comprehensive solution for integrating banking data, enabling actionable insights through effective ETL operations and dynamic reporting tools.
