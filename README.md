#1. Sample End-to-End data engineering project
- Apple Data Analysis
1. Using databricks environment
  - Create a cluster
  - Switch on DBFS
  - Upload required cvs and parquet files
  - Create delta table

2. Understand Low Level Design (LLD) of writing codebase in DE
  - Understand Factory pattern
  - Create one abstract reader which will use factory pattern

3. Designing Code base
  - Required extractor, transformer, and loader classes
  - Required utils class

4. Spark Concepts
  - spark session
  - Row Vs Column formats
  - Broadcast Join
  - Narrow Vs Wide Transformation
  - Job status and task

5. Apache Spark Concepts
  - Repartition Vs. Coalesce
  - PartitionBY Vs. Bucketing
  - Spark UI
  - DataLake Vs Data Lakehouse
  - Using Optimizing technique like predicate pushdown, predicate pruning

6. Different Business logic
  - customer who have bought Airpods after buying iPhone
  - customers who have bought both Airpods and iPhone
  - List all the products bought by customers after their initial purchase
