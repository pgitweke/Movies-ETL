# Movies-ETL

## Overview of Project

The aim of this project was to refactor the previous code to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data and performs the ETL process by adding the data to a PostgreSQL database.

Below is an overview of the steps we took to through the ETL process:

- Write an ETL function to read three data files,
- Extract and transform the Wikipedia data,
- Extract and transform the Kaggle and rating data,
- Load the data to a PostgreSQL Movie Database.

## Resources and Before Start Notes:

    Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv 
    Data Tools: PostgreSQL, pgAdmin
    Software: pgAdmin 11.17 - 1, Python 3.7.6 and Jupyter Notebook 


## Results

An ETL function is written to read in the three data files and then used to convert the Wikipedia JSON file to a Pandas DataFrame, and the DataFrame. The function is then used to convert the Kaggle metadata file and MovieLens ratings data file to a Pandas DataFrame, and the DataFrame is displayed. In both deliverable two and three, we extracted, transformed and merged the wikipedia data with the Kaggle metadata. Finally, the cleaned data was stored in PostgreSQL using python. 
