# YouTube-Analysis-Project-Data-Engineering
Data Engineering Project

## Objective:
The objective of this project is to build a data pipeline that can securely manage, streamline, and analyze YouTube video data. The data to be used in this project is structured and semi-structured YouTube video data. This data includes information such as the video title, description, tags, views, likes, dislikes, and comments.

## Project Goal:
1. Data ingestion: The first step is to ingest the data from YouTube. This can be done by using the YouTube Data API. The API allows you to extract data about videos, channels, and other aspects of YouTube.
2. ETL system: Once the data has been ingested, it needs to be transformed into a format that can be easily analyzed. This is done by an ETL (Extract, Transform, Load) system. The ETL system will clean the data, remove any errors, and transform it into a format that can be stored in a data lake.
3. Data lake: The data lake is a centralized repository where the data is stored. The data lake should be scalable so that it can handle the increasing amount of data.
4. Scalability: The data engineering system should be scalable so that it can handle the increasing amount of data. This can be done by using cloud computing services, such as AWS.
5. Cloud: The data engineering system should be hosted in the cloud so that it can be accessed from anywhere. This is also beneficial because the cloud can provide the scalability and computing power that is needed to process large amounts of data.
6. Reporting: The final step is to build a dashboard to visualize the data. This will allow you to get answers to the questions that you have about the data.

## AWS Services used:
1. Amazon S3: Amazon S3 is a scalable, durable, and secure object storage service that offers a broad set of features. Amazon S3 can store any amount of data, and it can be scaled up or down as needed. Amazon S3 is designed to store data for a long time, and it is resistant to data loss. Amazon S3 uses a variety of security features to protect your data, including encryption, access control, and auditing.
2. AWS IAM: AWS IAM is a service that helps you manage access to your AWS resources. It allows you to create and manage users, groups, and permissions.
3. AWS Glue: AWS Glue is a serverless data integration service that helps you discover, prepare, and combine data for analytics, machine learning, and application development. It can automatically discover data in your S3 buckets and create a schema for it.
4. AWS Lambda: AWS Lambda is a serverless computing service that allows you to run code without provisioning or managing servers. It is a good choice for running short-running, event-driven applications.
5. AWS Athena: AWS Athena is an interactive query service that allows you to analyze data stored in Amazon S3 using standard SQL. It is a serverless service, which means that you do not have to manage any infrastructure.
6. QuickSight: Amazon QuickSight is a business intelligence (BI) service that allows you to analyze data and create visualizations. It is a serverless service, which means that you do not have to manage any infrastructure.

## Dataset Used:
The Kaggle dataset we have used contains data on daily trending YouTube videos for several months. The data is divided into separate files for each region. Each file contains information about the trending videos for that region, such as the video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count. The dataset also includes a JSON file for each region that maps the category_id field to the corresponding category name.

(https://www.kaggle.com/datasets/datasnaek/youtube-new)
