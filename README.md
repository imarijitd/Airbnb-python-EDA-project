# Airbnb-python-EDA-project

## Project Overview
This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Numpy, Matplotlib, Seaborn for cleaning, visualization, and analysis.
![Airbnb Logo](https://github.com/user-attachments/assets/2333476d-967e-46b6-b4ab-8965e7a15eaf)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## About Dataset - 
The dataset contains 20,765 records and 22 columns.

The columns are -
**• id:** Unique identifier for each listing
• name: Title of the Airbnb listing
• host_name: Name of the host
• neighborhood_group: Group (borough) where the listing is located
• latitude/longitude: Geolocation of listings
• price: Nightly rental price
• room_type: Type of accommodation (e.g., entire home, private room)
• reviews_per_month: Average monthly reviews for the listing
• availability_365: Number of available days in the year


## Project Steps - 

### 1. Setting Up the Environment
Tools Used: Snowflake, AWS, SQL, PowerBI, MS Excel
Goal: Create a structured workspace within Snowflake and organize project folders for smooth development and data handling.


### 2. Creating AWS S3 bucket
Goal : We need to create AWS S3 bucket and load data into it. Follow the below steps -

a.) Go to AWS----> Options----> All Services----> S3, and click on "Create Bucket" option, and load data into the bucket after bucket creation.

b.) Create Role in AWS by going to option IAM----> Roles.

c.) Go to Snowflake and create integration object for connecting Snowflake with AWS.

d.) Go to AWS and replace 'USER_ARN' and 'EXTERNAL_ID' fields with the values received in Snowflake after integration object creation.
    
Follow : AWS----> IAM----> Roles----> Edit Roles----> Replace the values----> Save


### 3. Integrating Snowflake with AWS S3
Goal : We need to integrate Snowflake with AWS S3 by creating an integration object. Follow the code written in the text file fo more understanding.
The text file with name "AWS snowflake integration.txt" has been uploaded here for reference.


### 4. Loading data from AWS S3 to Snowflake
Goal : We need to create database, schema, tables and staging object in Snowflake for loading the data from AWS S3 bucket to Snowflake.
Follow the text file with name "loading data from aws to snowflake.txt" for more understanding.

