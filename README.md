# Data Engineering - YouTube
The objective of this project is to securely manage and streamline structured and semi-structured data from YouTube videos. The analysis will focus on video categories and trending metrics.

## Architecture
![Source: Darshil Parmar](https://github.com/GabrielBrionesL/de-aws-youtube/blob/main/architecture%20diagram.png)

## Project Goals
1. Data Ingestion — Develop a machanism for gathering data from diverse sources
2. ETL System — Transform raw data into the appropriate format for analysis
3. Data Lake — Establish a centralized repository to store data obtained from various sources
4. Scalability — Ensure that our system can expand seamlessly as our data volume grows
5. Cloud — Utilize cloud infrastructure, specifically AWS, for processing large datasets beyond the capacity of local machines.

## AWS Services:
1. Amazon S3: An object storage service by Amazon offering manufacturing scalability, data availability, security, and performance.
2. AWS IAM: Identity and Access Management (IAM) by AWS facilitates secure management of access to AWS services and resources.
3. AWS Glue: A serverless data integration service simplifying the discovery, preparation, and combination of data for analytics, machine learning, and application development
4. AWS Lambda: A computing service enabling programmers to run code without the need for server creation or management.
5. AWS Athena: An interactive query service for S3, eliminating the need to load data as it remains stored in S3.

## Kaggle Dataset
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

This dataset is a daily record of the top trending YouTube videos.
https://www.kaggle.com/datasets/datasnaek/youtube-new

## Blog
You can read more about this project [here](https://medium.com/@gabrielbrionesloria/building-a-scalable-data-engineering-pipeline-for-youtube-data-analysis-b2fd8adea318)

Thank you to [Darshil Parmar for the guidance](https://www.youtube.com/watch?v=yZKJFKu49Dk&list=PLBJe2dFI4sguF2nU6Z3Od7BX8eALZN3mU) 
