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

**Data Source:** [customer_shopping_behavior.csv](https://github.com/kavana-ar/Customer-Shopping-Behavior-Analysis/blob/main/customer_shopping_behavior.csv)

## Technologies

The following technologies were used to build this project:

* **Programming Language:** Python, SQL
* **Data Processing:** Pandas
* **Development Environment:** Jupyter Notebook
* **Database Connection:** SQLAlchemy, Psycopg2
* **Data Visualization:** Power BI

## Data Pipeline Architecture

The project follows the workflow below:

<img width="1774" height="887" alt="ChatGPT Image Sep 13, 2026, 01_23_43 PM" src="https://github.com/user-attachments/assets/d903d6f4-a798-4426-a39d-89c02a1b6891" />

Files in the following stages:

* Step 1: [Data Extraction](#step-1-data-extraction)
* Step 2: [Data Validation and Preparation](#step-2-data-validation-and-preparation)
* Step 3: [Data Storage](#step-3-data-storage) 
* Step 4: [SQL Analysis](#step-4-sql-analysis)
* Step 5: [Dashboard](#step-5-power-bi-dashboard)


## Step 1: Data Extraction

Collected customer shopping behavior data containing customer, product, purchase, payment, and transaction details.

Link to the script: [customer_shopping_behavior.csv](https://github.com/kavana-ar/Customer-Shopping-Behavior-Analysis/blob/main/customer_shopping_behavior.csv)

## Step 2: Data Validation and Preparation

Cleaned and prepared the data by handling missing values, duplicates, incorrect data types, and inconsistent entries for analysis.

Link to the script: [Customer_Shopping_Behavior_Analysis.ipynb](https://github.com/kavana-ar/Customer-Shopping-Behavior-Analysis/blob/main/Customer_Shopping_Behaviour_Analysis.ipynb)

## Step 3: Data Storage

After completing the data validation process, I loaded the datasets into a PostgreSQL database.

Python was used to connect to PostgreSQL and load the datasets into the database for SQL analysis.


## Step 4: SQL Analysis

Analyzed customer shopping data using SQL to identify sales trends, customer behavior, product performance, and key business insights.

Link to the script: [customer_behavior_analysis.sql](https://github.com/kavana-ar/Customer-Shopping-Behavior-Analysis/blob/main/customer_behaviour_analysis.sql)

## Step 5: Power BI Dashboard

After completing the SQL analysis, I developed an interactive dashboard using Power BI. which you can view [here](https://github.com/kavana-ar/Customer-Shopping-Behavior-Analysis/blob/main/customer_behavior_dashboard.pbix)




