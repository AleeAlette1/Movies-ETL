# Movies ETL

## Objective
Create an automated pipeline that takes in new data, performs the appropriate transformations and loads the data into existing tables. 

## Project Overview
Refractor code to create one function that takes in three files - Wikippedia Data, Kaggle Metadata and MovieLens Rating Data - and performs the ETL process by adding the data to a PostgreSQL database. 

## Results
- The function takes the three csv files and creates three separate DataFrames. 
- Extracted and Transformed the Wiikipedia data by filtering out TV shows, consolidated redundant data and removed any duplicates then formatted the Wikipedia data. 
- Extracted and Transformed both the Kaggle and Ratings data by also consilidating redundant data, removing any dupplicates and formatting and grouping the data. 
- Merged the Kaggle and Ratings data with the Wikipedia Dataframe.
- Loaded the data into a PostgreSQL database. 