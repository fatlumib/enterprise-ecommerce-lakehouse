# enterprise-ecommerce-lakehouse

🚀 Enterprise E-Commerce Lakehouse Platform
📌 Project Overview

This project simulates an enterprise-level data engineering platform using a Lakehouse architecture.

The system processes both batch and streaming data to support real-time and historical analytics for an e-commerce company.

Built using:

Databricks Community Edition

Delta Lake

PySpark

Structured Streaming

GitHub for version control

🏗️ Architecture

The platform follows the Medallion Architecture:

🥉 Bronze Layer → Raw ingestion (CSV/JSON)

🥈 Silver Layer → Cleaned & transformed data

🥇 Gold Layer → Business-level aggregated tables

🔥 Features Implemented

20+ Tables (Dimensions + Facts)

Incremental batch loads

Change Data Capture (MERGE INTO)

Slowly Changing Dimension Type 2

Structured Streaming

Window aggregations

Delta optimization (OPTIMIZE, ZORDER, VACUUM)

Time travel

🧱 Data Model

Star Schema including:

Dimension Tables

dim_customers

dim_products

dim_sellers

dim_suppliers

dim_regions

dim_time

dim_payment_methods

dim_shipping_providers

dim_warehouses

Fact Tables

fact_orders

fact_order_items

fact_payments

fact_shipments

fact_returns

fact_reviews

fact_inventory

fact_clickstream

fact_cart_events

fact_promotions

📊 Business KPIs

Daily revenue

Customer lifetime value

Seller performance

Inventory turnover

Conversion rate

Churn rate

🎯 Goal

Simulate a real-world enterprise data engineering system using modern lakehouse architecture principles.
