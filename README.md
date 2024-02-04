# Crowdfunding_ETL
Project 2 (Crowdfunding ETL) - Team 3 

A collaborative project to build an ETL pipeline using Python, Pandas and PostgresSQL for extracting, transforming and loading crowdfunding data from Excel files into a relational database.

## Introduction

In this project, We practiced building an ETL pipeline to process crowdfunding data from Excel files. We extracted and transformed the data, created csv files and then used the csv files to create an Entity Relationship Diagram(ERD) and a table schema. Finally, We loaded the CSV files into a PostgresSQL database.

## Features

- Extract and transform data of crowdfunding and contact table from excel files.
- Create and export category, Subcategory, Campaign and Contact Dataframes as CSV files.
- Design an ERD and table schema for the database.
- Create PostgresSQL database tables.

## Installation

- Clone the Repositorty.
- Install the required Python packages: 'Pandas', 'Anaconda'.
- Set up a PostgresSQL server and create a new database called 'crowdfunding.db'

## Usage

1. Run the Jupyter Notebook to extract and transform data, and create CSV files.
2. Use the provided `crowdfunding_db_schema.sql` file to create tables in the PostgreSQL database.
3. Load the CSV files into the corresponding PostgreSQL tables.
4. Query the database to verify the data has been loaded correctly.

## Built With

- Python
- Pandas
- PostgreSQL
- Jupyter Notebook
- Excel
