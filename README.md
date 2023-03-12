# Sparta Global Data Pipeline (ETL) - Final Project

This project is a data pipeline that extracts data from an S3 bucket using Boto3, processes the data using Pandas, and loads it into MongoDB.


## Requirements
- Python 3.x
- Pip
- Boto3
- Pandas
- PyMongo
- csv

## Installation
> Clone this repository.
> Install the requirements using pip: pip install -r requirements.txt.


## Usage
1. Extracting data from S3

> Connect to AWS and retrieve the list of CSV files in the S3 bucket.

2. Processing data with Pandas

> Clean and transform the data.

3. Loading data into MongoDB

> Use pymongo to insert the data into the MongoDB collection.
> Create a new MongoDB collection for the academy data.

4. Updating Academy Data

> Disclaimer: academy_clean.csv contains fake data and is used for learning purposes only. 

## Conclusion

This data pipeline provides a reliable and scalable solution for extracting, processing, and loading data from AWS S3 to MongoDB. It can be extended and customised to fit a wide range of use cases and requirements.