# football_top_scorers_etl

This Python script fetches top scorers data from the RapidAPI Football API, processes it into a pandas DataFrame, and stores it in a MySQL database.

## Features:

Retrieves top scorers data from a specified league and season.
Transforms the data into a structured format.
Establishes connection to a MySQL database.
Creates the table if it doesn't exist.
Inserts or updates data in the database table.


### Requirements:

Python 3.12.3
pandas library
requests library
mysql-connector-python library
dotenv library (to manage environment variables)
A RapidAPI account and API key