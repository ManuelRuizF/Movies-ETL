# Movies-ETL

## IMPORTANT NOTE
**Both Meta Data and Ratings CSV´s are in Zip files. So in order to open them, they need to be extracted**

Within the scope of the Amazing Prime Hackathon, this project will create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. It then performs the appropriate transformations and loads the data into an existing PostgreSQL database.
For this analysis, we used the following breakdown:

write an ETL function to read three data files,
extract and transform the Wikipedia data,
extract and transform the Kaggle and rating data,
load the data to a PostgreSQL Movie Database.

## Overview of the project  
- I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I had to refactor the code to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
We did the Extract- Transform-Load (ETL) on a movie database for a company named Amazing Prime.  
Amazing prime wants to give the cleaned data to the contestants of an intern  contest.

## Results
To accomplish this task we needed to export our cleaned data to Postgres and go through the number of rows.  
This is the results for both, movies and ratings tables.  
### Movies
![movies_tables](https://github.com/ManuelRuizF/Movies-ETL/blob/main/resources/movies_table_count.PNG)  

### Ratings
![ratings_tables](https://github.com/ManuelRuizF/Movies-ETL/blob/main/resources/ratings_query.PNG) 

### Resources
Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3, PostgreSQL 11.9, pgAdmin 4


