Data1202 Individual Project 1
Bhargavkumar Chaudhari - 100999175


Instructions
The objective of this assignment is simple:

- Create a GitHub repository with a README.md and at least 1 python file from a previous week.

Week 8 lab file.

In this Lab, you will learn how to use Python (pandas) for preprocessing your data when Imported from a SQL databease. By the end of this lab, you will be familiar with the connection methods and how you can run SQL Queries using Python.

This lab focuses on using Python for data analytics, specifically on how to connect to a SQL database and import data for analysis. The first step involves importing essential Python libraries handling and analyzing data, enabling a MySQL database connection, setting up a high-level interface to manage database communication.

The next key step is setting up the database engine using create_engine.
'With the connection in place, a SQL query is run using pd.read_sql_query(). This method fetches data from the table loads it directly into a pandas DataFrame called df. 
Once the data is loaded, df.head() is called to display the first five rows of the dataset. This provides a quick preview of the structure and contents of the data, helping users validate that the data has been imported correctly.
Finally, the shape of the dataset is evaluated using df.shape, which returns a tuple containing the number of rows and columns in the DataFrame. This gives users an overview of the dataset's size and is helpful for planning how to process and analyze it further. 

**Prerequisites**
Python 3.8+
Jupyter Notebook
MySQL Server

This project runs in a local Jupyter environment. Ensure your MySQL service is running and the database schema matches the lab requirements.

Bhargavkumar Chaudhari
100999175

Acknowledgement
Prof. Omar Al-Trad
