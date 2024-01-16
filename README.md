# Streaming News Sentiment Analysis ETL Pipeline

Welcome to the Real-Time News Sentiment Analysis project! This project implements an end-to-end ETL (Extract, Transform, Load) pipeline using Apache Kafka, PySpark, and MySQL for real-time sentiment analysis of news articles. The pipeline involves data ingestion from the New York Times API, sentiment analysis using PySpark streaming, and visualization of sentiment trends through a Tableau dashboard.

## Technologies Used
1. Apache Kafka: Utilized for building a scalable and distributed streaming platform to handle real-time data streams from the New York Times API.

2. PySpark: Employed PySpark for real-time sentiment analysis on the ingested news data streams.

3. MySQL: Established a MySQL database for efficient storage of analyzed sentiment data.

4. Tableau: Created a Tableau dashboard to visualize public sentiment trends based on the stored data.

## Features
Kafka Producer: Implemented a Kafka Producer for data ingestion from the New York Times API, ensuring a constant flow of near real-time news articles for analysis.

PySpark Streaming: Utilized PySpark streaming capabilities to perform sentiment analysis on the incoming news data, providing immediate insights into public sentiment.

MySQL Database: Established a MySQL database to efficiently store the analyzed sentiment data, enabling historical analysis and trend tracking.

Tableau Dashboard: Constructed a Tableau dashboard for insightful visualization of public sentiment trends over time, enhancing the interpretability of the analysis results.
