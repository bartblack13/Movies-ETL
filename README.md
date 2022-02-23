# Movies-ETL
ETL, python, Pandas, SQL for Hackathon prep

## Overview
The purpose of this project was to gain familiarity with the "Extract, Transform and Load" (ETL) pipeline with in the data analytics industry, and practive using it.  This was done as part of my week 8 project for my DU Data Analytics Bootcamp.  This module required  that I do the following:
* Create an ETL pipeline from raw data to a SQL database.
* Extract data from disparate sources using Python.
* Clean and transform data using Pandas (practiced defining my own functions, both with the def method and with the lambda method; and used list comprehension and for loops)
* Use regular expressions (regex) to parse data and to transform text into numbers.
* Load data with PostgreSQL; set up jupyter notbook to communicate with pgAdmin

In order to do this, I helped a mock company called AmazingPrime video, develope an algorithm to predict which low budget movie being released will become popular,
so that they can buy the streaming rights at a bargain.  AmazingPrime will use the data that I generated to sponsor a hackathon where participants will predict the popular pictures.
I was given the following 2 data sets:
* wikipedia- a scrape of all movies released since 1990; in json format
*	movielands website - rating data; as csv file

I extracted data from the sources, cleaned the data (removed unwanted columns due to missing values, unwanted info, or corrupted values), transformed into a single data set, and loaded the data into a SQL tables.  The cleaned and transformed tables were as follows:
* movies - containing 6,052 rows of data (see Figure 1)
* rating- containing 26,024,289 rows of data (see Figure 2)<br><br>

![This is an image](https://github.com/bartblack13/Movies-ETL/blob/main/Resources/movies_query.png)<br><br>
**(Figure 1)**<br><br>
![This is an image](https://github.com/bartblack13/Movies-ETL/blob/main/Resources/ratings_query.png)<br><br>
**(Figure 2)**
