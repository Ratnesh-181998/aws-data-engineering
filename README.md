# Complete Data Engineering With AWS - Basic To Advance

Master the art of Data Engineering with this comprehensive, **40-Session** project-driven course. Designed to take you from basic to advanced levels, this course covers the most in-demand technologies in the data world, focusing on AWS Cloud, Big Data, and Modern Data Stack.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,mysql,aws,gcp,spark,kafka,mongodb,cassandra,airflow,githubactions" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=Databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
</p>

---

## 🛠️ Module-wise & Class-wise Curriculum

### 📦 Module 1: SQL
*   **Class 1: Introduction to Databases**
    - What is Database?
    - Difference between Transactional Databases and NoSQL databases
    - What is DBMS & RDBMS?
    - Transactions & ACID Properties
    - Setup MySQL Workbench
    - Setup MySQL Using Docker
    - DDL, DML, DQL, DCL
    - CREATE Command
    - INSERT Command
    - Integrity Constraints
*   **Class 2: Advanced SQL Commands**
    - Alter Command
    - Drop, Truncate and Delete
    - Primary Key vs Foreign Key
    - Referential Integrity
    - Select Query, In-Built Functions, Aliases
    - UPDATE Command
    - Auto Increment in create table
    - Limit
    - Order By Clause
    - Conditional Operators
    - Logical Operators
    - Like Operation
    - User Defined Functions (UDFs)
*   **Class 3: Logic, Aggregation & Joins**
    - IS NULL, IS NOT NULL
    - Group By, Having Clause
    - Group Concat, Group RollUP
    - Sub Queries, IN and NOT IN
    - CASE-When
    - SQL Joins
*   **Class 4: Modern & Performance SQL**
    - Exists and Not Exists
    - Window Functions
    - Frame Clause
    - Coalesce Function
    - Common Table Expressions - Iterative and Recursive

### 📦 Module 2: BigData Fundamentals, Hadoop & Hive
*   **Class 1: BigData & Hadoop Core**
    - BigData Fundamentals
    - 5 V’s of BigData
    - Distributed Computation
    - Distributed Storage
    - Cluster, Commodity Hardware
    - File Formats
    - Types of Data
    - History of Hadoop
    - Hadoop Architecture & Components
*   **Class 2: Map-Reduce & YARN**
    - Map-Reduce Architecture
    - YARN Architecture
*   **Class 3: Apache Hive (Storage & Batch)**
    - Hive Complete Architecture
    - Hadoop Cluster Setup on GCP (Dataproc)
    - Data Types in Hive
    - Create Database & Create Table
    - Load Data From Local & HDFS
    - Internal Table vs External Table
    - Array & Map Data Types
    - SerDe in Hive (CSV, JSON, Parquet, ORC)
    - Static & Dynamic Partitioning
    - Bucketing
    - Joins: Map-Side, Bucket Map, Sorted Merge, Skew Join

### 📦 Module 3: Confluent Kafka
*   **Class 1: Real-time Data Streaming**
    - Kafka Cluster Architecture: Brokers, Topics, Partitions
    - Producer-Consumer, Consumer Group
    - Offset Management
    - Replicas, Commits (Sync & Async)
    - Confluent Kafka Setup & Topic Creation
    - Schema Registry
    - Key, Value Message (Random & Constant Keys)
    - Kafka Producer Code with Serialisation
    - Kafka Consumer Code with De-Serialization
    - Working with JSON, CSV Data
    - GCP Pub-Sub Setup (Producer & Consumer)

### 📦 Module 4: NoSQL DataBase: MongoDB & Cassandra
*   **Class 1: MongoDB Mastery**
    - CAP Theorem
    - What is MongoDB and MongoDB Atlas?
    - MongoDB vs Relational Database
    - MongoDB Architecture (Node, Data Centre, Cluster)
    - Data Replication, Write & Read Operation, Indexing
    - MongoDB Atlas & Compass Setup
    - Queries on MongoDB Collection from Python Application
*   **Class 2: KSQLdb & Real-time NoSQL**
    - KSQLdb in Confluent Kafka
    - Streams & Tables in KSQLdb
    - Persistent Queries & JOIN queries on streams
    - McDonald's Payments Stream data ingestion from Kafka to MongoDB
    - Setup windowed JOIN streams using KSQLdb
    - Setup MongoDB Sink Connector
*   **Class 3: Apache Cassandra**
    - What is Apache Cassandra?
    - Cassandra vs Relational Database
    - Architecture: Commit log, Mem-table, SSTable, Data replication
    - Data Partitioning and Token, VNodes
    - Consistency: Write & Read consistency in Cassandra
    - Partition Key, Cluster Key, Row Key Declaration
    - Cassandra Setup Using Docker & DataStax

### 📦 Module 5: Apache Spark (PySpark)
*   **Class 1: Spark Core Architecture**
    - Problems with Hadoop Map-Reduce
    - What is Apache Spark? Properties of RDD
    - Spark Ecosystem & Data Partitioning
    - Transformation (Narrow vs Wide) & Action
    - Lazy evaluation & Lineage graph (DAG)
    - Spark Web UI: Job, Stage and Task
    - Spark with Standalone vs YARN Cluster Manager
    - Deployment modes of Spark Application
*   **Class 2: Spark Optimization**
    - Persist and Caching (Storage Levels)
    - Data skewness & Techniques (Key Salting)
    - Repartition vs Coalesce
    - RDD vs Dataframe vs Dataset
    - Spark-Submit Utility
    - Memory management: Executor Container components
    - Resource allocation case studies
*   **Class 3: PySpark Development & Streaming**
    - Spark Session, Custom Schema, Read/Write (HDFS, Parquet)
    - Dataframe Operations: withColumn, Filter, Drop Duplicates, Joins
    - Window functions, Broadcast join
    - Spark Structured Streaming: Stateless vs Stateful
    - Output modes, Triggers, Checkpointing
    - Global & Windowed aggregation, Watermarking
    - Pipeline: Kafka Topic to MongoDB

### 📦 Module 6: Apache Airflow
*   **Class 1: Pipeline Orchestration**
    - What is orchestration in BigData?
    - Dependency management in Data Pipeline design
    - Architecture & Components of Airflow
    - Operators: BashOperator, PythonOperator
    - How to write Airflow DAG Scripts
    - Parallel task execution
    - Setup Airflow on GCP using Composer
    - End-to-End Exercise: Dataproc Cluster Management + PySpark Job

### 📦 Module 7: Databricks
*   **Class 1: Cloud Data Intelligence**
    - What is Databricks?
    - Unity Catalog, Delta Lake & Delta Tables
    - Workspace & Metastore Setup
    - Managed & External Catalog Setup
    - Volumes in Databricks
    - PySpark Notebook Setup & Volume Access
    - CRUD using DeltaTable Python API
    - Time travel & Delta Sharing

### 📦 Module 8: Data Warehousing
*   **Class 1: Data Modeling & Architecture**
    - OLAP vs OLTP
    - Data Warehouse vs Data Lake vs Data Mart
    - Fact Tables vs Dimension Tables
    - Slowly changing Dimensions (SCD Type 1, 2, 3)
    - Star, Snowflake, and Galaxy Schema Design
    - **Case Study 1:** Expedia Advanced Modeling
    - **Case Study 2:** Swiggy Advanced Modeling

### 📦 Module 9: Snowflake & BigQuery
*   **Class 1: Snowflake Cloud Warehouse**
    - UI Walkthrough & Data Loading
    - SnowPipe for Event-driven ingestion
    - External Stages (Google Storage Bucket)
    - Tasks & Scheduled execution
*   **Class 2: Google BigQuery**
    - BigQuery Fundamentals & Architecture (Capacitor, Dremel)
    - Internal vs External Tables
    - Managed Table Operations: Partition & Cluster Keys
    - AI Features: Gemini AI assisted Query (Data Canvas)
    - Medallion Architecture Pipelines (Bronze, Silver, Gold)
    - Data Ingestion from GCP Pub-Sub via Dataflow

### 📦 Module 10: AWS Cloud Services
*   **Section 1: Core Infra**
    - S3: Bucket Creation, ARN, AWS CLI, Modern Lakehouse S3 Tables
    - Lambda: Hello World, Testing, S3 Triggers, Layers, Boto3 logic
    - IAM: Users, Roles, Policies
*   **Section 2: Messaging**
    - SNS: Topics, Email Subscription, Lambda publishing
    - SQS: Basics, SQS vs Kafka, Lambda Read
    - Event Bridge: Scheduled triggers & Pipes
*   **Section 3: Database & Analytics**
    - RDS: MySQL setup, Python manipulate data
    - Athena: Athena vs Spark, Querying S3 via Glue Catalog
    - Redshift: Architecture, Load/Unload, manifests, Redshift Spectrum
*   **Section 4: ETL & ETL Orchestration**
    - AWS Glue: Glue Catalog, Glue Crawler, Visual ETL, Job Bookmarks
    - Step Functions: Lambda Orchestration, Error Handling
    - EMR: Hive/Hadoop access, Spark jobs via EMRStepOperator

### 📦 Module 11: Apache Iceberg & Hudi
*   **Class 1: Modern Lakehouse Formats**
    - Small file problem & Open table format solutions
    - **Apache Iceberg:** Metadata layer vs Data Layer, CRUD operations, CoW vs MoR, Time Travel, Compaction
    - **Apache Hudi:** ACID Guarantees, Incremental Pipelines, Storage Layout, Snapshot/CDC Queries

### 📦 Module 12: Apache Flink
*   **Class 1: Real-time Stream Processing**
    - Flink APIs: DataStream, Table, SQL
    - Architecture: Job Manager, Task Managers, Parallelism
    - State Management & Checkpointing (Exactly-once)
    - Backpressure: Monitoring & Tackling

### 📦 Module 13: Industrial Projects (15 Projects)
*   **✅ Project - 1: Flight Booking Data Pipeline with Airflow & CICD (Covered In Module 6)**
    - Tech Stack: GitHub, GitHub Actions, Google Storage, PySpark, Dataproc Serverless, Airflow, BigQuery
*   **✅ Project - 2: E-commerce Event-Driven Data Pipeline (Covered In Module 7)**
    - Tech Stack: Databricks, PySpark, Delta Lake, Databricks Volumes, Databricks Workflows, GitHub
*   **✅ Project - 3: Travel Booking SCD2 Data Warehouse (Covered In Module 7)**
    - Tech Stack: Databricks, PySpark, Delta Lake, Unity Catalog, PyDeequ (For Data Quality Checks), Databricks Volumes, Databricks Workflows
*   **✅ Project - 4: Healthcare DLT Medallion Pipeline (Covered In Module 7)**
    - Tech Stack: Databricks DLT, Delta Lake, SQL, Unity Catalog, Expectations, Databricks Workflows
*   **✅ Project - 5: UPI Transactions CDC Streaming Analytics (Covered In Module 7)**
    - Tech Stack: Databricks, PySpark Structured Streaming, Delta Lake (Change Data Feed), Unity Catalog
*   **✅ Project - 6: News Data Analysis with Event-Driven Incremental Load in Snowflake Table (Covered In Module 9)**
    - Tech Stack: Airflow, Google Cloud Storage, Python, Snowflake
*   **✅ Project - 7: Car Rental Data Batch Ingestion with SCD2 Merge in Snowflake Table (Covered In Module 9)**
    - Tech Stack: Python, PySpark, GCP Dataproc, Airflow, Snowflake
*   **✅ Project - 8: Movie Booking CDC data real time aggregation in Snowflake Dynamic Table (Covered In Module 9)**
    - Tech Stack: Python, Snowflake Dynamic Table, Snowflake Stream, Snowflake Tasks, Streamlit
*   **✅ Project - 9: Weather Forecast Data Processing (Cover In Module 9)**
    - Tech Stack: Python, OpenWeather API, GCP Composer (Airflow), PySpark, Dataproc Serverless, BigQuery, Google Cloud Storage (GCS), GitHub, GitHub Actions
*   **✅ Project - 10: Ad Tech Real Time Data Analysis Project**
    - Tech Stack: Python, AWS Kinesis, AWS Managed Flink, AWS Glue, Spark Streaming, Apache Iceberg, AWS S3, Glue Catalog, AWS Athena
*   **✅ Project - 11: Betting App Real Time Data Analysis Project**
    - Tech Stack: Python, AWS Kinesis, AWS Managed Flink, AWS Data Firehose, AWS S3, Glue Catalog, AWS Athena
*   **✅ Project - 12: Quality Movie Data Analysis Project**
    - Tech Stack: S3, Glue Crawler, Glue Catalog, Glue Catalog Data Quality, Glue Low Code ETL, Redshift, Event Bridge, SNS
*   **✅ Project - 13: Airline Data Ingestion Incrementally**
    - Tech Stack: Python, AWS S3, AWS Step Function, AWS Glue, AWS Glue Crawler, AWS Glue Catalog, AWS Redshift, AWS Event Bridge, AWS SNS
*   **✅ Project - 14: Crypto Data Analysis Near Realtime Data Pipeline**
    - Tech Stack: Python, AWS DynamoDB, AWS Kinesis, AWS Data Firehose, AWS Lambda, AWS S3, AWS Glue, AWS Glue Catalog
*   **✅ Project - 15: Credit Card Transactional Analysis For Fraud Risk**
    - Tech Stack: Python, PySpark, Google Storage, GCP Dataproc Serverless, GCP BigQuery, GCP Composer (Airflow), PyTest, GitHub, GitHub Actions (For CI/CD)

