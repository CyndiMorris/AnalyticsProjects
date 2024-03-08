# Project: WeRateDogs - Python, Data Wrangling & Analysis

## Project Details


Skills demonstrated in the [WeRateDogs](https://github.com/CyndiMorris/AnalyticsProjects/blob/main/WeRateDogs/WeRateDogs.ipynb) project:  



## Analysis and Statistics

Question 1:
What are the top 5 most common breeds?  
  * by tweet, retweet, favorite counts

Question 2:
What is the most popular dog stage?  
  * by tweet, retweet, favorite counts

Question 3:
What are the top 5 most popular dog names?  
  * by tweet

## Datasets




## Software and Packages

Python  
Pandas  
NumPy  
JSON  
Requests  
Matplotlib  
Seaborn  
Jupyter Notebook


## Files





A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. 

They'd like a Postgres database created with tables designed to optimize queries on song play analysis




The Star Schema consists of:   
* (1) fact table: **`songplays`**  
* (4)dimension tables: **`songs`, `artists`, `users` and `time`**  
** Contain the primaray keys which will be used to reference back to the fact table.


Down below, you can see the entity relationship diagram(ERD) in the form of a star schema. 

On why to use a relational database for this case:

- The data types are structured
- The amount of data we need to analyze is not big enough to require big data related solutions.
- This structure will enable the analysts to aggregate the data efficiently
- Ability to use SQL that is more than enough for this kind of analysis
- We need to use JOINS






Project Instructions
Schema for Song Play Analysis
Using the song and log datasets, you'll need to create a star schema optimized for queries on song play analysis. This includes the following tables.

Fact Table
songplays - records in log data associated with song plays i.e. records with page NextSong
songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent
Dimension Tables
users - users in the app
user_id, first_name, last_name, gender, level
songs - songs in music database
song_id, title, artist_id, year, duration
artists - artists in music database
artist_id, name, location, latitude, longitude
time - timestamps of records in songplays broken down into specific units
start_time, hour, day, week, month, year, weekday
Project Template
To get started with the project, go to the workspace on the next page, where you'll find the project template files. You can work on your project and submit your work through this workspace. Alternatively, you can download the project template files from the Resources folder if you'd like to develop your project locally.

In addition to the data files, the project workspace includes six files:

test.ipynb displays the first few rows of each table to let you check your database.
create_tables.py drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts.
etl.ipynb reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.
etl.py reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook.
sql_queries.py contains all your sql queries, and is imported into the last three files above.
README.md provides discussion on your project.
Project Steps
Below are steps you can follow to complete the project:

Create Tables
Write CREATE statements in sql_queries.py to create each table.
Write DROP statements in sql_queries.py to drop each table if it exists.
Run create_tables.py to create your database and tables.
Run test.ipynb to confirm the creation of your tables with the correct columns. Make sure to click "Restart kernel" to close the connection to the database after running this notebook.
Build ETL Processes
Follow instructions in the etl.ipynb notebook to develop ETL processes for each table. At the end of each table section, or at the end of the notebook, run test.ipynb to confirm that records were successfully inserted into each table. Remember to rerun create_tables.py to reset your tables before each time you run this notebook.

Build ETL Pipeline
Use what you've completed in etl.ipynb to complete etl.py, where you'll process the entire datasets. Remember to run create_tables.py before running etl.py to reset your tables. Run test.ipynb to confirm your records were successfully inserted into each table.

Document Process
Do the following steps in your README.md file.

Discuss the purpose of this database in the context of the startup, Sparkify, and their analytical goals.
State and justify your database schema design and ETL pipeline.
[Optional] Provide example queries and results for song play analysis.
Here's a guide(opens in a new tab) on Markdown Syntax.

NOTE: You will not be able to run test.ipynb, etl.ipynb, or etl.py until you have run create_tables.py at least once to create the sparkifydb database, which these other files connect to.

Project Introduction:

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. 

They'd like a Postgres database created with tables designed to optimize queries on song play analysis


Project Summary:

Define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.

 
Database/Tables:

The star schema will be centered around the fact table songlplays with dimensions tables of songs, users, artists and time. 

songplays table: user, artist, song info; (songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent)

users table: user info; (user_id, first_name, last_name, gender, level)
songs table: song info; (song_id, title, artist_id, year, duration)
artists table: artist info; (artist_id, name, location, latitude, longitude)
time: song play time info; (start_time, hour, day, week, month, year, weekday)


Files:

sql_queries.py: SQL queries to build fact and dimension tables; enter data.
create_tables.py: code to create, drops tables and reset tables before running ETL code. 
etl.ipynb:  jupiter notebook working file for ETL processes; develop and run the python code for the etl.py file.
etl.py: code to populate tables with data from JSON files song_data and log_data.
test.ipynb: jupiter notebook interactive file to test the SQL database queires.


ETL:

1. song_files
    * insert song records
    * insert artist records
    
2. log_files
    * insert time records
    * insert user records
    * insert songplay records; songid & artistid from song and artist tables.
    


References:
https://learn.udacity.com/nanodegrees/nd002-wgu-2/parts/54b031dc-b8aa-4092-a4d2-2675bd1d7098/lessons/a2baadf9-a931-46d0-acd8-9997f911c35b/concepts/5da6136b-1443-4f4e-a024-7613a8c1173c

https://learn.udacity.com/nanodegrees/nd002-wgu-2/parts/54b031dc-b8aa-4092-a4d2-2675bd1d7098/lessons/a2baadf9-a931-46d0-acd8-9997f911c35b/concepts/cc2e800f-0d4e-4a9a-b265-d1f654815036
