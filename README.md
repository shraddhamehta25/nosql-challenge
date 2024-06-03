# nosql-challenge
NoSQL_setup_starter.ipynb:

Database and Jupyter Notebook Setup:

The notebook sets up the environment for MongoDB interaction and data analysis using PyMongo and Pandas.
It imports necessary libraries like MongoClient from PyMongo, pd from Pandas, and pprint for pretty printing.
It creates an instance of the MongoClient to connect to the MongoDB server.
The uk_food database is selected and assigned to a variable named db.
The collections within the database are reviewed, and the establishments collection is assigned to a variable named establishments.

Update the Database:

It adds a new restaurant entry to the database with a pending rating and then updates its BusinessTypeID.
It removes establishments within the Dover Local Authority from the database.
It converts certain string fields to numeric types (latitude, longitude, and RatingValue) using update_many.
NoSQL_analysis_starter.ipynb:

Exploratory Analysis:

Question 1: It finds establishments with a hygiene score of 20, displays the count, and prints the first document.
Question 2: It finds establishments in London with a RatingValue greater than or equal to 4, displays the count, and prints the first document.
Question 3: It finds the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the "Penang Flavours" restaurant. It converts the result to a DataFrame.
Question 4: It calculates the number of establishments in each Local Authority area with a hygiene score of 0, displays the count, and prints the first 10 results.
These notebooks provide a comprehensive analysis of the UK Food Standards Agency data, including data setup, database updates, and exploratory analysis. They leverage PyMongo for MongoDB interaction and Pandas for data manipulation and analysis, ensuring an effective exploration of the dataset.
