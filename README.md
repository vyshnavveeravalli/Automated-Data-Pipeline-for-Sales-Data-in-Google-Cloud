# Google Cloud Data Analytics Project


This project showcases a comprehensive data pipeline for sales data, leveraging the power of Google Cloud Platform (GCP) services. The pipeline effectively automates the process of ingesting, processing, and visualizing sales data, providing valuable insights for decision-making.

Key Components and Functionality

Web Portal (Flask): A user-friendly web application built with Python Flask allows users to upload sales data files in CSV or Excel format.
Google Cloud Storage (GCS): Uploaded files are securely stored in a GCS bucket, ensuring data durability and accessibility.
Google Cloud Function: A serverless function triggered by file uploads processes the data, performs necessary transformations, and loads it into BigQuery.
BigQuery: A fully managed, NoSQL data warehouse that stores and analyzes the processed sales data efficiently.
Looker Studio: A powerful data visualization tool that creates interactive dashboards and reports based on the data in BigQuery, providing actionable insights.



![image](https://github.com/vishal-bulbule/sales-data-pipeline-project/assets/143475073/613ef050-9538-4a87-98f5-95694e87455e)

## Architecture

![image](https://github.com/vishal-bulbule/sales-data-pipeline-project/assets/143475073/7ec3e2ec-f981-4fe4-9b3e-2c48dcbcdf0a)
