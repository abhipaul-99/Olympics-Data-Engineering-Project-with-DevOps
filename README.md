# Olympics-Data-Engineering-Project-with-DevOps

# Azure End-to-End Data Engineering Project with CI/CD

## Overview

This project demonstrates a complete Azure Data Engineering solution built using the Paris Olympics 2024 dataset. It covers the entire data lifecycle from data ingestion to transformation, curation, and deployment while implementing CI/CD best practices using Azure DevOps.

## Architecture

**Source Systems**

* GitHub Repository
* Azure Data Lake Storage Gen2
* CSV Datasets (Athletes, Coaches, Events, NOCs)

**Data Ingestion**

* Azure Data Factory (ADF)
* Parameterized & Dynamic Pipelines
* Data Validation Framework
* CI/CD Integration with Azure DevOps

**Data Storage**

* Bronze Layer (Raw Data)
* Silver Layer (Transformed Data)
* Gold Layer (Curated Business Data)

**Data Processing**

* Azure Databricks
* PySpark Transformations
* Dynamic Notebooks
* Databricks Workflows

**Data Modeling**

* Delta Lake Architecture
* Delta Live Tables (DLT)
* Medallion Architecture (Bronze → Silver → Gold)

## Key Features

* End-to-end Azure Data Engineering implementation
* Dynamic and parameterized Azure Data Factory pipelines
* Azure DevOps integration for version control and CI/CD
* Feature Branch, Pull Request, and Release workflow
* PySpark-based data transformation framework
* Delta Live Tables for Gold layer creation
* File format optimization (CSV to Parquet)
* Real-world data validation and monitoring scenarios

## Technologies Used

* Azure Data Factory
* Azure Data Lake Storage Gen2
* Azure Databricks
* PySpark
* Delta Lake
* Delta Live Tables (DLT)
* Azure DevOps
* Git
* Azure Portal

## Dataset

Paris Olympics 2024 Dataset:

* Athletes
* Coaches
* Events
* NOCs (Countries)

## Learning Outcomes

* Building scalable Azure Data Pipelines
* Implementing CI/CD for Data Engineering Projects
* Working with Medallion Architecture
* Performing Big Data Transformations using PySpark
* Creating Dynamic Data Engineering Workflows
* Managing Azure Resources and Storage
* Deploying Data Solutions using Azure DevOps

## Project Workflow

1. Extract data from source systems
2. Ingest data into Bronze Layer using ADF
3. Convert CSV files into optimized Parquet format
4. Apply PySpark transformations in Databricks
5. Create enriched entities in Silver Layer
6. Build curated datasets in Gold Layer using DLT
7. Manage source control through Azure DevOps
8. Deploy changes through CI/CD pipelines

## Author

Abhishek Paul
Azure Data Engineer | Databricks | PySpark | Azure Data Factory
