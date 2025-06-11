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

## Author
Venugopal Reddy Gangula
