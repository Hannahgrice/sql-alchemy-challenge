# sql-alchemy-challenge Climate Data Analysis and Flask API
Overview
This project involves climate data analysis using Python and SQLAlchemy and creating a Flask API.

Part 1: Analyze and Explore the Climate Data
Database Connection:

Connected to hawaii.sqlite using SQLAlchemy create_engine().
Reflected tables using SQLAlchemy automap_base() and linked to Python with a session.
Precipitation Analysis:

Found the most recent date.
Queried the last 12 months of precipitation data.
Loaded results into a Pandas DataFrame, sorted by date, and plotted the data.
Printed summary statistics.
Station Analysis:

Calculated total stations.
Found the most-active stations and their observation counts.
Queried temperature data for the most-active station and plotted as a histogram.
Part 2: Design Your Climate App

