# Home_Sales

## Overview
This project aims to analyze home sales data using PySpark, a powerful distributed data processing framework. The dataset contains information about home sales, including attributes such as date, price, number of bedrooms and bathrooms, square footage, and more. By leveraging PySpark's capabilities, I was able to perform various analyses and gain insights into the housing market.

## Features
- Data Loading: The project includes code to load the home sales data from a CSV file stored in an AWS S3 bucket into a PySpark DataFrame.
- Data Transformation: PySpark DataFrame APIs are used to perform data transformation tasks such as filtering, aggregating, and partitioning.
- SQL Queries: PySpark SQL module is utilized to execute SQL queries for complex analysis tasks.
- Caching: The project demonstrates how to cache DataFrame and SQL temporary tables for improved query performance.
- Partitioning: The dataset is partitioned based on the date_built field to optimize query performance and improve data organization.
- Parquet Format: The data is written to Parquet files for efficient storage and retrieval.
- Analysis: Various analysis tasks are performed, including computing average prices, filtering data based on specific criteria, and calculating runtime for queries.
- Documentation: The project includes detailed documentation and comments to explain the code and analysis steps.

## Requirements
- Python 3.x
- Apache Spark
- PySpark
- Jupyter Notebook or any Python IDE
- Java jdk-17

--
**Source Data: 

Chat GPT Provider: OpenAI Model Version: GPT-3.5 Training Data: Diverse internet text Training Duration: Training duration was about 2-3 hours @article{openai2023, author = {OpenAI}, title = {ChatGPT: A Language Model by OpenAI}, year = {2023}, url = {https://www.openai.com}, }

Class Videos

Stackoverflow