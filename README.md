# OpenWeather Data Pipeline Using Apache Airflow, Python, Amazon S3, and Amazon EC2

This project demonstrates an end-to-end pipeline for extracting weather data from the OpenWeather API, transforming it using Python, and loading the results into Amazon S3. The project is orchestrated with Apache Airflow and makes use of Amazon EC2 for a virtual server in the cloud.

![image](https://github.com/user-attachments/assets/ccdaf74e-1f9d-458a-ba96-54b96104af55)

# Key Technologies

**Apache Airflow:** Orchestrating the entire pipeline.

**Python:** Processing and transforming the extracted data.

**Amazon S3:** Storing processed data.

**Amazon EC2:** Virtual server in the cloud

**VS Code:** To write codes and establish connection

**OpenWeather API:** Source of weather data.

# Pipeline Overview

The pipeline follows these steps:

**1. Extract Data:** Fetches weather data for a list of cities from the OpenWeather API and loads it into a PySpark DataFrame.

**2. Process Data:** Normalizes the raw JSON data into a tabular format and saves the data in Amazon EC2 server.

**3. Transform Data:** Reads the processed data from EC2 server, applies transformations, and prepares it for loading into Amazon S3 bucket.

# Final Pipeline

![image](https://github.com/user-attachments/assets/6c9abb7b-3ef2-4867-abe5-fd69b5fe8317)



