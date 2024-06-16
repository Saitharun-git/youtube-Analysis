## Spark-Youtube-Analysis

### Overview
The objective of this project is to securely manage, streamline, and analyze structured and semi-structured YouTube video data. This will be done by categorizing videos based on their content and trending metrics.

### Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

### AWS services
- **Amazon S3:** Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
- **AWS IAM:** This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
- **QuickSight:** Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
- **AWS Glue:** A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
- **AWS Lambda:** Lambda is a computing service that allows programmers to run code without creating or managing servers.
- **AWS Athena:** Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

### Dataset Used
The Kaggle dataset comprises statistical information in CSV format regarding daily trending YouTube videos spanning several months. Each day, up to 200 popular videos are released across various locations, with data for each region stored in separate files. The dataset includes details such as video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. Additionally, a category_id field specific to each region is provided in the JSON file associated with the respective area.

[Kaggle Dataset Link](https://www.kaggle.com/datasets/datasnaek/youtube-new)

### Architecture Diagram

![Architecture Diagram](architecture.jpeg)


