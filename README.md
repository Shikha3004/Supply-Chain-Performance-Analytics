# Global Supply Chain Performance & Optimization Analytics

## 📌 Project Overview

This project focuses on analyzing global supply chain operations using Power BI to identify inefficiencies in delivery performance, product profitability, and regional sales distribution.

The goal is to transform raw operational data into actionable insights that help optimize logistics strategies and improve decision-making.

---

## 📊 Dataset Details

This project uses the **DataCo Smart Supply Chain dataset**, which contains over **180,000 supply chain transactions** including:

* Customer orders
* Product information
* Shipping and delivery performance
* Sales and profit metrics
* Geographic distribution

The dataset will be transformed into a structured **star schema model** to support advanced analytics.

---

## 🎯 Problem Statement

A global retail company is experiencing inefficiencies in its supply chain operations, including delayed deliveries, inconsistent product performance, and uneven regional sales distribution. These inefficiencies impact customer satisfaction, operational costs, and profitability.

The organization requires a centralized analytics dashboard to monitor supply chain performance and enable data-driven decision-making.

---

## ✅ Project Objectives

* Analyze end-to-end supply chain performance
* Evaluate delivery efficiency and delay risks
* Assess product and category profitability
* Monitor regional sales trends
* Develop KPI-driven dashboards for operational optimization

---

## ❓ Key Business Questions

* Which regions experience the highest delivery delays?
* What factors contribute to late shipments?
* Which products generate the highest profits?
* How does shipping mode impact performance?
* What are the trends in sales over time?

---

## 🛠 Tools & Technologies

* Power BI
* Power Query
* DAX
* Data Modeling (Star Schema)

---
## 🔧 Data Preparation & Modeling Steps

The following steps were performed to transform the raw dataset into an analytics-ready star schema model:

### 1. Data Loading

* Imported raw supply chain CSV dataset into Power BI
* Verified data types and column formats
* Disabled raw table from report view to maintain clean model structure

### 2. Data Cleaning in Power Query

* Removed unnecessary columns from raw dataset
* Eliminated duplicate rows in dimension tables
* Standardized column names and data types
* Created structured dimension tables from raw data

### 3. Star Schema Design

Created the following tables:

**Fact Table**

* Fact_Sales (transaction-level sales data)

**Dimension Tables**

* Dim_Customer
* Dim_Product
* Dim_Geography
* Dim_Shipping
* Dim_Date (custom date table)

### 4. Date Table Creation

* Generated a custom date dimension using Power Query
* Added Year, Quarter, Month, and Day attributes
* Connected date table to order date (active relationship)
* Created inactive relationship for shipping date (advanced modeling)

### 5. Relationship Modeling

* Built one-to-many relationships between fact and dimension tables
* Implemented proper primary keys and foreign keys
* Ensured clean star schema structure for optimized performance

### 6. Data Model Optimization

* Removed redundant columns from fact table
* Created composite geography key for unique relationships
* Validated referential integrity
* Organized model for scalable analytics

---

This structured modeling enables efficient KPI calculation, advanced DAX measures, and interactive dashboard design.

## 📈 Project Status

🔄 Project planning and data modeling phase

Dashboard development in progress.
