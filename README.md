# uber_data_analytics 🚗


This Uber data analytics project utilizes the latest available TLC Trip Record Data from November 2024, 
sourced from the NYC Taxi and Limousine Commission (TLC). 


The data, collected by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP), 
specifically focuses on Yellow Taxi Trip Records.

## Project Overview
Data Source: The project uses a parquet file named "yellow_tripdata_2024-11.parquet" extracted from the TLC website, representing data from November 2024.
Data Modeling: The raw data has been transformed into a structured format, creating fact and dimension tables to facilitate efficient analysis and querying.

<img width="500" alt="nyc_gov_site" src="https://github.com/user-attachments/assets/0e41f500-4f93-481e-b733-47fa6c4f9f33" /> <img width="372" alt="nov_2024_data" src="https://github.com/user-attachments/assets/20fa737b-3736-4ddb-b11d-2908bbc76e11" /> <img width="508" alt="data_dict" src="https://github.com/user-attachments/assets/f4cf3924-ec11-49e7-9f8e-6ca0f7c9126e" />

## Current Progress
Data Processing: The initial data processing, including the creation of fact and dimension tables, has been completed using Jupyter Notebook (.ipynb file). This approach allows for interactive development and testing of the data transformation logic.
Data Model Visualization: An Entity Relationship Diagram (ERD) has been created using Lucid, utilizing the Entity Relationship table option from the shapes menu. This diagram visually represents the structure of the fact and dimension tables, illustrating the relationships between different data entities in the project.

<img width="500" alt="data_model" src="https://github.com/user-attachments/assets/c6194384-0c3c-4fae-bc48-dc87c6793764"/>


## Technology Stack:

Google Cloud Platform: Provides the cloud infrastructure for data storage and processing

Mage AI: Used for data pipeline orchestration and transformation

Google Looker: Employed for data visualization and business intelligence


