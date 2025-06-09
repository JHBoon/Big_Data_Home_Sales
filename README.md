Spelling and grammar check only. show a list of the changes you  made: Big Data Analysis with PySpark – Home Sales Project

TOPIC:Big Data - PySpark &S QL

Overview
This project focuses on analyzing large-scale housing data using PySpark and distributed computing principles. 
It was completed as the final assignment for the Data Analytics Bootcamp at the University of California, Irvine.


Goal
This project demonstrates how PySpark can be used to perform scalable, efficient analysis on large datasets. It highlights key techniques used in big data analytics, including distributed querying, in-memory caching, and optimized data storage formats.


Key components:

Loading and processing data with PySpark

Running SQL-style queries using Spark SQL

Caching and optimizing in-memory performance

Saving data in a partitioned Parquet format

Working with AWS-hosted datasets and distributed storage

Technologies Used
Python 3.12

PySpark (SparkSession, Spark SQL, SparkFiles)

Apache Spark

Apache Parquet

AWS S3 (for data access)

Visual Studio Code

ChatGPT+ and Xpert Learning Assistant + AI

Dataset
Source:
https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv

Description:
The dataset includes housing sales data with features such as:

id
date 
date_built
price
Number of bedrooms and bathrooms
Square footage
Number of floors
Waterfront and view indicators

Key Objectives
Load and Inspect Data

Downloaded and read the dataset into a PySpark DataFrame

Inferred schema and validated structure

Data Analysis Using PySpark

Performed filtering, grouping, and aggregation using DataFrame and SQL APIs

Analyzed average home prices based on key housing attributes

SQL Integration

Registered the DataFrame as a temporary table for SQL querying

Used caching to improve performance of repeated queries

Parquet Partitionin

Demonstrated improved efficiency for large-scale reads

Caching and Resource Management

Cached and uncached SQL tables using Spark’s in-memory capabilities

Validated caching status and controlled memory usage

Author
Jay Boon
Data Analytics Bootcamp
University of California, Irvine – Module 22 - Big Data