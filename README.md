# youtube_data_analysis
DE project using AWS
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

Project Goals
Data Ingestion — Build a mechanism to ingest data from different sources
ETL System —  getting data in raw format, transforming this data into the proper format
Data lake —  getting data from multiple sources so  need centralized repo to store them
Scalability — As the size of our data increases, need to make sure our system scales with it
Cloud —  can’t process vast amounts of data on our local computer so we need to use the cloud, in this case,  will use AWS
Reporting — Build a dashboard

services used
Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3
