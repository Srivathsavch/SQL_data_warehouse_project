# SQL Data Warehouse Project

This repository contains an end-to-end **Data Warehouse (DWH)** project built using **SQL Server**, covering **ETL processes, data modeling, and analytics** following industry best practices.

---

## Project Overview

This project focuses on designing and implementing a scalable Data Warehouse using the **Medallion Architecture (Bronze, Silver, Gold layers)**.

### Key Components

* **Data Architecture:** 
  Designing a Data Warehouse using the Medallion Architecture (Bronze, Silver, Gold).

* **ETL Pipelines:**
  Extracting, transforming, and loading data from source systems into the Data Warehouse.

* **Data Modeling:**
  Developing fact and dimension tables optimized for analytical querying.

---

## Project Workflow

1. **Requirement Understanding**
   Analyzed business and data requirements before starting the implementation.

2. **Source Data & Architecture Design**

   * Source data consists of CSV files stored in two folders: `source_crm` and `source_erp`.
   * Data architecture and data flow were designed and visualized using **Draw.io**.

3. **Project Management**

   * Project tasks were created and tracked using **Notion** (similar to industry-level tools like JIRA) to ensure a systematic workflow.

4. **Naming Conventions**

   * Defined consistent naming conventions for **Schemas, Stored Procedures, Tables, Columns, and Views**.

5. **Database & Schema Setup**

   * Created a database named `DataWarehouse`.
   * Implemented three schemas: `bronze`, `silver`, and `gold`.

6. **Bronze Layer (Raw Data)**

   * Created tables in the `bronze` schema.
   * Loaded raw data from CSV files into bronze tables.
   * Performed data completeness checks.
   * Visualized the raw data flow in Draw.io.

7. **Silver Layer (Cleaned & Standardized Data)**

   * Identified and resolved data inconsistencies such as:

     * Extra spacing
     * NULL values
     * Invalid dates
     * Duplicates
     * Primary key issues
     * Incorrect calculations
   * Applied data cleaning, standardization, normalization, and enrichment.
   * Loaded refined data into `silver` schema tables.
   * Performed data quality validations.
   * Updated the data flow model accordingly.

8. **Business Understanding & Star Schema Design**

   * Analyzed business entities such as **Customer, Product, and Sales**.
   * Identified dimensions and facts.
   * Designed a **Star Schema** for analytical use cases.

9. **Gold Layer (Analytics-Ready Data)**

   * Integrated data by joining relevant silver tables.
   * Created analytical **views** in the `gold` schema.

10. **Final Analytics Layer**

    * Linked dimension tables with fact tables.
    * Prepared the final data model for business intelligence and analytics.

---

## About Me

Hi! I am **Srivathsav**, a motivated learner transitioning into the **Data Science** domain, with hands-on experience in:

* Python
* SQL
* NumPy
* Pandas
* Matplotlib

I completed this project under the able guidance of **@DataWithBaraa** and am thankful for the **insightful, helpful, and selfless effort** put into creating and sharing such valuable learning content with the community.

---

⭐ If you find this project useful, feel free to star the repository!
