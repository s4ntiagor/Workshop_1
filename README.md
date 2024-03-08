# Workshop_1

This is the repository in which I'll be showing the ETL process for the ETL's signature at Universidad Autonoma de Occidente. Here we will have to create the database, its tables as well as loading the data that has been modified from a CSV file according to the objectives of this excersice. This has been done in Jupyter notebooks.

#  Quick Data Overview

 We have been requested to start load the dataset which has 50,000 rows and 11 columns, which are the next ones:
 - First name, Last Name, Email, country, Application Date, Years of Experience (YOE), Seniority Level, Technology, Code Challenge Score, Technical Interview.

# Objectives

This workshop aimed to develop an ETL process that involves creating a relational database from a Python script. The script is responsible for creating the tables and loading them with the data that has been transformed from the CSV file to the Postgres database.

The workshop also aimed to produce visualizations of the following queries using PowerBI:
- Hires by technology (pie chart).
- Hires by year (horizontal bar chart).
- Hires by seniority (bar chart).
- Hires by country over years (USA, Brazil, Colombia, and Ecuador only).

# Technologies Used
- Python 3.1.1
- PostgresSQL 16
- pgAdmin 4

# How to run this workshop

- Make a copy of the repository with the command "git clone https://github.com/s4ntiagor/Workshop_1.git"
- Set up a virtual environment from your terminal. You can use: "python -m venv [environment_name]"
- Turn on your virtual environment. You can use: "[environment_name]/scripts/activate"
- Install the necessary tools and modules in the environment. Use: "pip install -r requirements.txt".
- Use the set up environment as kernel.

# Things to consider
- To connect to the database, you need a file named "config_db.json" with your database credentials in json format. This file should have the following credentials: "localhost" for the server address, "user" for the username, "password" for the password, and "database" for the specific database you want to access. Each key should have its corresponding credential value.
- You should have a csv with the data explained in the Quick Data Overview session to get results very close to those shown in this repository.
