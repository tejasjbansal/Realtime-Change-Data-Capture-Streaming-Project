## Realtime Change Data Capture Streaming Project

This project explores Change Data Capture (CDC) for real-time data streaming using a powerful technology stack. We build a data pipeline that captures changes in a PostgreSQL database and streams them for further processing.

### System Architecture

![Project Architecture](https://github.com/tejasjbansal/Realtime-Change-Data-Capture-Streaming-Project/assets/56173595/c455793e-e58f-4bde-a2e5-daa5fb6f5e6c)

### Project Goals

* Understand the concept of Change Data Capture (CDC).
* Implement a real-time data streaming pipeline using Docker containers.
* Leverage Debezium to capture changes from the PostgreSQL database.
* Utilize Apache Kafka as a high-throughput messaging system.
* Explore Apache Spark for potential downstream data processing tasks (not included in this project but can be extended).
* Integrate Slack for real-time notifications (optional).

### Technologies

* **Docker:** Containerizes the various components for a consistent and portable environment.
* **PostgreSQL:** Acts as the source database where simulated financial transactions are stored.
* **Debezium:** Captures changes (inserts, updates, deletes) from the PostgreSQL database.
* **Kafka:** Acts as a distributed streaming platform to buffer and deliver change data events.
* **Apache Spark (Optional):** Provides a framework for large-scale data processing on the streamed data.
* **Slack (Optional):** Enables real-time notifications about data changes (e.g., new transactions).

### Data Generation

A Python script utilizes the `faker` library to generate realistic financial transactions and insert them into the PostgreSQL database. This script provides a foundation for testing and simulating CDC functionality.

###  Further Exploration

This project provides a starting point for exploring real-time data streaming with CDC. You can extend it by:

* Implementing downstream processing with Apache Spark.
* Integrating real-world data sources and target systems.
* Customizing the data processing logic based on your specific needs.

We encourage you to delve deeper into the individual technologies and explore their functionalities in the context of CDC and real-time data pipelines.
