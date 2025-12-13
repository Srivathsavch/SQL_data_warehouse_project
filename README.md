SQL_data_warehouse_project
This is Data Warehouse project.
Building DWH with SQL server, including ETL processes, data modelling and analytics.

Project overview:
This project involves:
1.Data Architecture - Designing a Data Warehouse using Medallioan architecture Bronze, Silver, Gold.
2.ETL Pipelines - Extracting, transforming and loading data from source systems into warehouse.
3.Data Modelling - Developing fact and dimension tables which are integrated for analytical purposes.

Project Work flow:
1.Understanding the requirements 
2.Choosing the data management approach.In this case we have CSV files as the source data in two folders source_crm, source_erp with contains the CSV data files. The data architecture is drawn using Draw.io 
3.Then the project tasks are been created using Notion (like industry level JIRA software) to track the work flow and be systematic in what we do.
4.The Naming conventions are made to be integrated with the specific name we use for Stored Procedures, Schemas, Tables, Columns, Views.
5.Creating a Database ‘DataWarehouse’ and three schemas ‘bronze’, ‘silver’, ‘gold’.
6.In the first step we create tables in the bronze schema and load the data from our CSV files to the tables, check for the data completeness and visualize the same in the Draw.io. Now we are ready with the raw data in the bronze layer
7.In the next step we try to understand the data inconsistencies like (spacing, NULLs, invalid dates, duplicates, unique Primary keys, improper calculations etc) typically known as data cleaning, data standardization, data normalization, data enrichment for each tables in the bronze and load the cleaned data into the silver layer tables which we create under silver schema and perform data quality checks. The whole data flow will be updated in the data flow model.
8.In the last step we explore the business objects , here in case we have customer, product, sales and understand their dimensions and followed star schema data modelling, updated in the data flow model.
9.As a part of data modelling we try to join the tables (data integration) and create views for them in the gold schema using the silver schema tables.
10.At the end we link the dimension tables with the fact tables which will be available ready for the business analytics



About me:
Hi! I am Srivathsav, a motivated learner transitioning into Data Science domain, with hands-on experience in Python, SQL, Numpy, Pandas and Matplotlib.
I completed this project under the able guidance of @DataWithBaraa and am very much thankful for creating and sharing such insightful, helpful, selfless content.


