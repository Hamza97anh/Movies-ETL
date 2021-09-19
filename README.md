# Movies-ETL
## Technologies
- Python
- Jupyter Notebook
- Kaggle
- JSON
- SQL
- Excel
## Project Overview
ETL stands for Extract, Tranform, and Load. This project is an exercise in using this method. We use Jupyter Notebook and Pyhon to manipulate data found via public sources like kaggle and wikipedia. One the data is cleaned we import it into PgAdmin to create a series of tables or queries using SQL.  
## Results

Here we see a table showing all the movies in our data with various informations about the movies.

![Movies_query](https://github.com/Hamza97anh/Movies-ETL/blob/d537319ef396d4d99d0252a28ab952d3d7751c5b/Resources/movies_query.PNG)

From this main table we created another query with information pulled from our movies query and some from other tables. 

![ratings_query](https://github.com/Hamza97anh/Movies-ETL/blob/d537319ef396d4d99d0252a28ab952d3d7751c5b/Resources/ratings_query.PNG)

# Summary
Both Python and SQL have their strengths. For a more efficient and seemless project, the usage of both can be very advantagous. For Data cleaning it's preferred to use Python as it has all the built in tools needed and lots of support as its the most commonly used langauage in the industry. When it comes to rapidly creating tables within your database, SQL is better suited for that as it's designed with that function in mind.For this project we had eight or more csvs in our database. Where as in Python we had to import each datatable and then right long codes to merge. SQL can do so with as little as 3-4 lines, more if you're writing a more complex quary code. That's why it's always good to have all the tool for the job.  
