# sqlalchemy-challenge
Module10
Used Python and SQLAlchemy to do basic climate analysis and data exploration for the given Hawaii climate database. The following analysis were completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

Using the provided starter notebook and hawaii.sqlite files, climate analysis and data exploration is completed.
SQLAlchemy create_engine is used to connect to the sqlite database.
SQLAlchemy automap_base() is used to reflect the tables into classes and saved a reference to those classes: Station and Measurement.
Python is linked to the database by creating an SQLAlchemy session.
Precipitation Analysis is done by:


Station Analysis is done by:

Designing a query to calculate the total number of stations in the dataset.
Designing a query to find the most active stations (i.e. which stations have the most rows?).
Listing the stations and observation counts in descending order.


Part 2 Design Your Climate App 

After completion of initial analysis, a Flask API based on the queries developed above is designed using Flask to create routes. All available routes are listed in the home page. The query results are converted into a dictionary using date as key and precipation as value for the precipation data and returned the JSON represenation of the dictionary. Similarly, JSON list are returned for stations, temperature observations (tobs) for previous year.