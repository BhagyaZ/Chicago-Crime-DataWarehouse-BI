
# Chicago Crime Data Warehouse & BI Analytics

## 📌 Overview
This project implements an end-to-end Data Warehousing and Business Intelligence solution for analyzing Chicago crime data.

## 🏗️ Architecture
Source Data (CSV, Excel, SQL) → SSIS ETL → SQL Server Data Warehouse → SSAS Cube → Excel OLAP → Power BI Reports

## 📊 Features
- Star schema data warehouse design
- ETL pipelines using SSIS
- Slowly Changing Dimension (Type 2)
- SSAS multidimensional cube
- OLAP operations (roll-up, drill-down, slice, dice, pivot)
- Power BI dashboards with advanced analytics

## 🧰 Technologies
- SQL Server
- SSIS
- SSAS
- Power BI
- Excel

## 📈 Key Components
- Fact Table: FactCrime
- Dimensions: DimDate, DimLocation, DimCrimeType, DimCommunityArea
- Measures: Total Crimes, Avg Process Time


## 🚀 Outcome
Built a complete BI pipeline enabling multi-dimensional analysis and interactive reporting for crime data.
