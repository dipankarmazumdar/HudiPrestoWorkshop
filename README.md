# Building an Open Data Lakehouse on AWS S3 with Apache Hudi & Presto
---
In this hands-on workshop, we'll learn how to build a open lakehouse architecture using `Apache Hudi`, `PrestoDB` on a cloud data lake `Amazon S3`. Additonally, we will take advantage of Hudi's `metadata table` and `clustering` table service to optimally organize data in S3.

## Dataset
The workshop will leverage a 1 GB TPC-DS dataset to demonstrate the various capabilities of `read` and `write` operations with Hudi and Presto. The dataset is made available at a common S3 location (`s3://bucket`) accessible to workshop attendees.

## Environment Details
All the required open source software and its dependencies will be pre-installed for the workshop session. Attendees will use `Jupyter Notebook` to run various read and write queries on Apache Hudi using Presto and Spark SQL. Users will also have access to Presto UI for additional analysis and debugging.
![Example Image](img.jpg)


## Description
The lakehouse architecture combines the flexibility, scalability, and cost-efficiency of data lakes with the robust data management features of data warehouses. This workshop is designed to provide data engineers & architects with a comprehensive understanding of Apache Hudi and use it to build an open lakehouse architecture on AWS S3, utilizing Presto as the engine for fast and interactive queries.

## Key Takeaways
### Attendees will learn about:
- Open Lakehouse architecture stack with Hudi as the transactional layer & Presto as the compute engine.
- Hudi’s Table optimization service - Clustering & Metadata tables to help improve query performance.
- Practical exercises on creating different Hudi tables (CoW, MoR) on S3, ingesting data, performing upserts/deletes, and synching with catalogs such as Hive Metastore.
- Various ways of querying data using Presto including snapshot and read-optimized queries.
- Application of clustering table service & metadata table to observe firsthand improvements in query speed on the Presto-side.

## Getting Started
1. Link to the Jupyter notebook & PrestoUI will be provided in the workshop (replace it with your assigned `number`)
2. Navigate to `/notebooks/` & you will see the `Hudi_Presto_Workshop.ipynb` file. Some of you should see this directly when you open Jupyter.
3. Open the Notebook to follow the workshop instructor in executing the code
4. The `/notebooks/commons/` folder will contain another notebook `HudiUtilityFunctions.ipynb`. This is where we have all the utility functions. Some of you should see this directly when you open Jupyter.
5. Attendees SHOULD NOT CREATE any additional notebooks other than the ones provided in their environment
6. If at any point you are stuck & want to restart the entire session, go to `Kernel` & hit `Restart`. Then follow the sequence.
