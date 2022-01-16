# Movies-ETL
Module 8: Extract, Transform, Load

## Overview
Create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing database. Base code files were provided, we need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Process
1. Retrieve data.
2. Process data, it includes cleaning and removing unnecessary fields/columns.
3. Create a PostgreSQL Database (__movie_data__).
4. Export resulting movies DataFrame to PostgreSQL table __movies__.
5. Export full ratings CSV file into the PostgrSQL table __ratings__.

## Resources
* Data Source: 3 files were provided, and they were placed in a folder outside the project folder to avoid GitHub file size limitations.
    - movies_metadata.csv
    - ratings.csv
    - wikipedia-movies.json    
* Language:
  - Python 3.9.7
  - SQL (PostgreSQL), version 14 
* Libraries:
  - Pandas
  - Numpy
  - time
  - SQLAlchemy
  - psycopg2
  - re

* Development tools: 
  - Jupyter Notebook 6.4.6
  - Visual Code 1.62.3; just to edit README.md file.
  - PostgreSQL 14
  - pgAdmin 4 (6.1)

