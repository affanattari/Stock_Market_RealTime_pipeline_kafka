# Stock_Market_RealTime_pipeline_kafka
End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.
This Stock Market Kafka Real-Time Data Engineering Project involves processing stock market data using Apache Kafka and AWS services.

![Uploading Architecture.jpg…]()
 # Workflow Overview:
1. Producer (Stock Market Simulation & Kafka Integration)
A Python-based stock market simulator reads data from a CSV dataset.
Uses Boto3 SDK to interact with AWS.
Sends real-time stock data to Kafka hosted on Amazon EC2.

2. Kafka as a Messaging System
Acts as a message broker between producer and consumers.
Ensures efficient streaming of real-time data.

3. Consumer (Data Storage & Processing)
Kafka consumer stores data in Amazon S3 for further processing.
AWS Glue Crawler extracts metadata and updates the Glue Data Catalog.
Amazon Athena enables querying stock data using SQL for analysis and insights.

This project demonstrates an end-to-end real-time data pipeline using Kafka and AWS, enabling stock market analysis, trend detection, and decision-making.

# Dataset - 
https://www.kaggle.com/datasets/mattiuzc/stock-exchange-data
