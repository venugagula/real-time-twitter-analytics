# Real-Time Twitter Analytics Pipeline

## Overview
A real-time streaming pipeline that ingests live tweets (5,000+/min) using Azure Event Hubs and Spark Structured Streaming. Performs sentiment analysis and visualizes hashtag trends and geolocation sentiment using Power BI.

## Tech Stack
- Azure Event Hubs
- Azure Databricks
- Spark Structured Streaming
- Cosmos DB
- TextBlob / NLTK
- Power BI

## Key Features
- Streaming tweet ingestion & transformation
- Sentiment classification (Positive, Neutral, Negative)
- Live dashboards with trending hashtags and sentiment maps

## How to Run
1. Set up Event Hubs and Cosmos DB
2. Run Spark job in Databricks
3. Connect Power BI to Cosmos DB

## Architecture
![image](https://github.com/user-attachments/assets/a7c1800f-a4f1-426a-a1bc-ad733b1f5caa)

# Twitter API Credentials
TWITTER_CONSUMER_KEY=your_consumer_key
TWITTER_CONSUMER_SECRET=your_consumer_secret
TWITTER_ACCESS_TOKEN=your_access_token
TWITTER_ACCESS_TOKEN_SECRET=your_access_token_secret

# Kafka Configuration
KAFKA_BOOTSTRAP_SERVERS=kafka:9092
KAFKA_TOPIC=twitter-stream

# Spark Configuration
SPARK_MASTER_URL=spark://spark-master:7077

# MongoDB Configuration
MONGO_CONNECTION_STRING=mongodb://mongo:27017
MONGO_DATABASE=twitter
MONGO_COLLECTION=tweets

# Tweet Filters
TWEET_KEYWORDS=Scala,Apache,Spark,Kafka,Data,AI,BigData
TWEET_LANGUAGES=en

## Author
Venugopal Reddy Gangula
