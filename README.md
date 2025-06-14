# SCD_Implementation
Data Engineering Project

 Project Overview
This project implements a modern Data Lakehouse architecture on Microsoft Azure using the Medallion Architecture pattern (Bronze-Silver-Gold layers). The solution processes customer, product, and order data through multiple transformation stages, implementing Slowly Changing Dimensions (SCD) Type 1 and Type 2 using Delta



 Architecture Diagram


 ![image alt](https://github.com/siddhhartha/SCD_Implementation/blob/3c3adcd06fa4e1e13ed05389f8da2548f3c52179/Screenshot%202025-06-15%20000446.png)



Data Flow

1. Ingestion: Raw files (Orders, Products, Customers) → Bronze Layer
2. Transformation: Data cleansing and validation → Silver Layer
3. Modeling: SCD implementation and dimensional modeling → Gold Layer
4. Consumption: Analytics and reporting via Power BI
