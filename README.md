# 📈 Stock Market Real-Time Data Processing

## 🏗️ Project Overview  
This project sets up a **real-time stock market data pipeline** using **Apache Kafka**, **AWS S3**, **Glue**, and **Athena**.  
The pipeline fetches live stock data, processes it using Kafka, stores it in Amazon S3, and enables querying through Athena.  

## 🏛️ Architecture  
![Architecture](https://github.com/Puthipongyo/Stock-Market-Project/blob/main/Architecture.jpg)  

## ⚙️ Technologies Used  
- **Programming Language:** Python  
- **Cloud Platform:** Amazon Web Services (AWS)  
- **Services:**  
  - **Amazon S3** – Stores processed stock market data  
  - **Amazon Athena** – Queries and analyzes stored data  
  - **AWS Glue Crawler** – Extracts metadata from S3  
  - **AWS Glue Catalog** – Manages schema and metadata  
  - **Amazon EC2** – Hosts Apache Kafka  
  - **Apache Kafka** – Real-time data streaming  

