# Real-Time Data Streaming using Kafka

This project is based on a tutorial from YouTube on executing an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

## Introduction

In this project, you'll find an implementation of the tutorial mentioned above, utilizing various technologies such as Python, Amazon Web Services (AWS), EC2, Apache Kafka, Glue, Athena, and SQL.

## Architecture

The architecture of this project remains consistent with the one outlined in the original tutorial.
![Project Architecture](Architecture.jpg)
## Technology Used

- **Programming Language:** Python
- **Amazon Web Service (AWS):**
  - S3 (Simple Storage Service)
  - Athena
  - Glue Crawler
  - Glue Catalog
  - EC2
- **Apache Kafka**

## Dataset Used

You can use any dataset for this project, as the focus lies on the operation side of Data Engineering, specifically building a data pipeline. However, the tutorial provides a sample dataset, which can be found [here](https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv).

## Acknowledgement

This project is a direct implementation of the tutorial by Darshil Parmar. The video tutorial can be found [here](https://www.youtube.com/embed/KerNf0NANMo).

## Modifications

The original tutorial utilized Zookeeper for managing Kafka, whereas in this implementation, Kafka is configured to run in Kafka-only mode (Kraft mode) for simplified setup and management.
