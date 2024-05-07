# Data Engineering - YouTube
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Architecture
![Source: Darshil Pamar](https://github.com/GabrielBrionesL/de-aws-youtube/blob/main/architecture%20diagram.png)

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS

## AWS Servcies:
1. Amazon S3: An object storage service by Amazon offering manufacturing scalability, data availability, security, and performance.
2. AWS IAM: Identity and Access Management (IAM) by AWS facilitates secure management of access to AWS services and resources.
3. AWS Glue: A serverless data integration service simplifying the discovery, preparation, and combination of data for analytics, machine learning, and application development
4. AWS Lambda: A computing service enabling programmers to run code without the need for server creation or management.
5. AWS Athena: An interactive query service for S3, eliminating the need to load data as it remains stored in S3.

## Kaggle Dataset
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

This dataset is a daily record of the top trending YouTube videos.
https://www.kaggle.com/datasets/datasnaek/youtube-new
