# Movies_ETL
## Overview of the project
The task of the project is to create an automated ETL pipeline that creates a movie database based on structured and unstructured data. When writing the code, extract Wikipedia JSON data, Kaggle metadata and MovieLens rating data, use regular expressions and functions to transform the data, and then finally load the data into the PostgreSQL database.
### Results
The resulting database consists of two tables that are highlighted below.

The movies table with 6,052 rows of data, each representing a unique movie title. The table also includes 31 columns of data with production related information, such as, movie budget, producers, actors and release data.

![image](https://github.com/YutaiLee/Movies_ETL/blob/main/Resources/movies_query.png)
T
he ratings table a table with 26,024,289 rows of data, each representing a viewer rating of 1-5. The table also includes 5 columns of data such as movie title, rating and date. 

![image](https://github.com/YutaiLee/Movies_ETL/blob/main/Resources/ratings_query.png)
