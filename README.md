# 🛍️ Customer Shopping Behavior Analysis

## Objective

I analyzed customer shopping behavior to understand purchasing patterns, customer characteristics, product preferences, and other factors related to customer purchases.

The project follows an end-to-end data analysis process:

* Imported customer shopping data into Python.
* Explored and validated the dataset using Pandas.
* Identified and handled missing values.
* Cleaned and standardized column names.
* Created additional features such as age groups and purchase frequency in days.
* Loaded the cleaned data into PostgreSQL.
* Used SQL to analyze customer shopping behavior.
* Created an interactive Power BI dashboard to present the analysis and insights.

## Table of Contents

- [Data Source](#data-Source)
- [Technologies](#technologies)
- [Data Pipeline Architecture](#Data-Pipeline-Architecture)
- [Step 1: Data Extraction](#step-1-data-extraction)
- [Step 2: Data Validation and Preparation](#step-2-data-validation-and-preparation)
- [Step 3: Data Storage](#step-3-data-storage)
- [Step 4: SQL Analysis](#step-4-sql-analysis)
- [Step 5: Power BI Dashboard](#step-5-power-bi-dashboard)


## Data Source

This project uses a customer shopping behavior dataset obtained from the kaggle.

**Data Source:** [customer_shopping_behavior.csv]()

## Technologies

The following technologies were used to build this project:

* **Programming Language:** Python, SQL
* **Data Processing:** Pandas
* **Development Environment:** Jupyter Notebook
* **Database Connection:** SQLAlchemy, Psycopg2
* **Data Visualization:** Power BI

## Data Pipeline Architecture

The project follows the workflow below:

<img width="1665" height="836" alt="ChatGPT Image Aug 30, 2026, 02_00_29 PM" src="https://github.com/user-attachments/assets/3ae45b51-f7d3-47a2-98cf-616cee28b539" />

Files in the following stages:

* Step 1: [Data Extraction](#step-1-data-extraction)
* Step 2: [Data Validation and Preparation](#step-2-data-validation-and-preparation)
* Step 3: [Data Storage](#step-3-data-storage) 
* Step 4: [SQL Analysis](#step-4-sql-analysis)
* Step 5: [Dashboard](#step-5-power-bi-dashboard)


## Step 1: Data Extraction

Collected customer shopping behavior data containing customer, product, purchase, payment, and transaction details.

Link to the script: [customer_shopping_behavior.csv]()

## Step 2: Data Validation and Preparation

Cleaned and prepared the data by handling missing values, duplicates, incorrect data types, and inconsistent entries for analysis.

Link to the script: [Customer_Shopping_Behavior_Analysis.ipynb]()

## Step 3: Data Storage

After completing the data validation process, I loaded the datasets into a PostgreSQL database.

Python was used to connect to PostgreSQL and load the datasets into the database for SQL analysis.


## Step 4: SQL Analysis

Analyzed customer shopping data using SQL to identify sales trends, customer behavior, product performance, and key business insights.

Link to the script: [customer_behavior_analysis.sql]()

The SQL analysis includes the following steps.

## 1. Data Exploration

First, I viewed the available data in both tables:

<img width="1307" height="615" alt="Screenshot 2026-08-30 122932" src="https://github.com/user-attachments/assets/331bfecf-1772-4a3d-95a2-d5b5ac1122a8" />


## 2. Latest Four Completed Earnings Reports
<img width="1055" height="533" alt="Screenshot 2026-08-30 123903" src="https://github.com/user-attachments/assets/0153c5ca-a784-4cb0-831f-64de4677c39b" />


## 3. Stock Price on Each Earnings Date
<img width="1062" height="531" alt="Screenshot 2026-08-30 123934" src="https://github.com/user-attachments/assets/82cd0193-f05f-4523-a668-e5e3f01a700c" />


## 4. Stock Price Three Trading Days Before Earnings
<img width="1053" height="535" alt="Screenshot 2026-08-30 124028" src="https://github.com/user-attachments/assets/231d5b63-8c8c-4ca0-addc-e7e4f12b6ec1" />


## 5. Earnings-Day Closing Price
<img width="1066" height="548" alt="Screenshot 2026-08-30 124108" src="https://github.com/user-attachments/assets/ebc7fdb1-291f-4173-b06f-d4d0db6742cb" />


## Step 5: Power BI Dashboard

After completing the SQL analysis, I developed an interactive dashboard using Power BI. which you can view [here](https://github.com/kavana-ar/Financial-Modeling-Prep/blob/main/FMP_dashboard%20_1.pbix)

<img width="1358" height="656" alt="Screenshot 2026-08-30 125016" src="https://github.com/user-attachments/assets/3cef372d-850f-4441-be83-2959233e2426" />
<img width="1346" height="501" alt="Screenshot 2026-08-30 125042" src="https://github.com/user-attachments/assets/a09dede3-b832-422c-aa23-5829ea971a63" />




