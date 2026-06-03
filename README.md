# gcp-ecommerce-etl-pipeline
End-to-End ETL Pipeline on Google Cloud using Pub/Sub, Dataflow, BigQuery, Dataplex Governance and Looker Studio(Data Studio)

# End-to-End ETL Pipeline on Google Cloud

## Project Overview

Designed and implemented an end-to-end ETL pipeline on Google Cloud for processing e-commerce order data. The pipeline ingests source data, transforms records using Dataflow, stores analytics-ready datasets in BigQuery, applies governance using Dataplex, and delivers business insights through Looker Studio dashboards.

## Architecture

Simulated On-Prem Source / Cloud Storage → Pub/Sub → Dataflow → BigQuery → Dataplex Governance → Looker Studio

## Tech Stack

| Category       | Technology            |
| -------------- | --------------------- |
| Messaging      | Google Cloud Pub/Sub  |
| Processing     | Google Cloud Dataflow |
| Data Warehouse | BigQuery              |
| Governance     | Dataplex              |
| Visualization  | Looker Studio         |
| Language       | SQL                   |

## Pipeline Workflow

1. Simulated e-commerce order data from an on-prem source and staged datasets in Google Cloud Storage for development and testing.
2. Ingested data through Google Cloud Pub/Sub.
3. Processed and transformed records using Google Cloud Dataflow.
4. Stored analytics-ready fact and dimension tables in BigQuery.
5. Applied governance using Dataplex Lakes, Curated Zones, Asset Registration, Metadata Discovery, and Data Profiling.
6. Built Looker Studio dashboards for revenue, order, product, and seller analytics.

## Data Model

**Fact Table**

* fact_orders

**Dimension Tables**

* dim_customers
* dim_products
* dim_sellers

## Dashboard KPIs

* Total Revenue
* Total Orders
* Average Order Value
* Revenue by Product Category
* Revenue by Seller State

## Dataplex Governance

* Dataplex Lake & Curated Zone
* Asset Registration
* Metadata Discovery
* Data Profiling

## Screenshots

### Architecture
<img width="681" height="465" alt="image" src="https://github.com/user-attachments/assets/148958e2-759a-43f5-aa98-82f56612e6b7" />



### Dashboard
<img width="1204" height="578" alt="image" src="https://github.com/user-attachments/assets/4d4df1ef-2d11-4ea1-9d4c-2f2b482767c7" />



<img width="1051" height="356" alt="image" src="https://github.com/user-attachments/assets/7d2d786b-bf4f-4a58-8d6d-9a995e009e1c" />


### Dataflow
<img width="614" height="688" alt="image" src="https://github.com/user-attachments/assets/ddcda61b-55af-489c-b995-6d5a6c9e509f" />



### BigQuery
<img width="237" height="697" alt="image" src="https://github.com/user-attachments/assets/12471fb2-29ed-48b4-bba3-732d68c7a004" />




## Dataplex Governance

- Created Dataplex Lake and Analytics Zone
- Registered BigQuery datasets
- Enabled metadata discovery
- Performed data profiling
