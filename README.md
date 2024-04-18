# Airbnb_data_pipeline
End-to-end data engineering project for DE Zoomcamp 2024

Overview

This project aims to automate the ingestion of quarterly Airbnb listing data from [InsideAirbnb](https://insideairbnb.com/about) into a Redshift data warehouse and then visualize this data using AWS services. The process begins with data landing in an S3 bucket, Glue is utilized for data extraction, and transformation, and loaded into Redshift datawarehouse which is later used to visualize in Quicksight.



