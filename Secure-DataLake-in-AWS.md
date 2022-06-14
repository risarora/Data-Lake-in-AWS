# Step by step guide for setting up a data lake in AWS using Lake formation, Glue, DataBrew, Athena, Redshift, Macie etc.
## What you'll learn
* How to quickly setup a data lake in AWS using AWS Lake formation
* You will learn to build real-world data pipeline using AWS glue studio and ingest data from sources such as RDS, Kinesis Firehose and DynamoDB
* You will learn how to transform data using AWS Glue Studio and AWS Glue DataBrew
* You will acquire good data engineering skills in AWS using AWS lake formation, Glue Studio and, blueprints and workflows in lake formation

## Description
In this course, we will be creating a data lake using AWS Lake Formation and bring data warehouse capabilites to the data lake to form the lakehouse architecture using Amazon Redshift. Using Lake Formation, we also collect and catalog data from different data sources, move the data into our S3 data lake, and then clean and classify them.

The course will follow a logical progression of a real world project implementation with hands on experience of setting up  a data lake,  creating data pipelines  for ingestion and transforming your data in preparation for analytics and reporting.

## Chapter 1
* We will setup our data lake using lake formation
* Create different data sources (MySQL RDS and Kinesis)
* Ingest data from the MYSQL RDS data source into the data lake by setting up blueprint and workflow jobs in lake formation
* Catalog our Database using crawlers
* Use governed tables for managing access control and security
* Query our data lake using Athena

## Chapter 2,
* We will explore the use of AWS Gluw DataBrew for profiling and understanding our data before we starting performing complex ETL jobs.
* We will create Recipes for manipulating the data in our data lake using different transformations
* Clean and normalise data
* Run jobs to apply the recipes on all new data or larger datasets

## Chapter 3
* Introduce Glue Studio
* Author and monitor ETL jobs for tranforming our data and moving them  between different zone of our data lake
* Create a DynamoDB source and ingest data into our data lake using AWS Glue

## Chapter 4
* Introduce and create a redshift cluster to bring datawarehouse capabilities to our data lake to form the lakehouse architecture
* Create ETL jobs for moving data from our lake into the warehouse for analytics
* Use redshift spectrum to query against data in our S3 data lake without the need for duplicating data or infrastructure

## Chapter 5
* Introduce Amazon Macie for managing data security and data privacy and ensure we can continue to identify sensitive data at scale as our data lake grows
