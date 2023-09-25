# sqlite_database_operations
HHA 504 - Week 3 

Homework assignment #3: Introduction to the world of databases, starting with SQLite. Integrate data processing with Python, utilize Pandas for exploratory data analysis, and conduct database operations using SQLite.

**Summary:**
- Details on the datasets:
    1. Used datasets from New York Presbyterian Hospital and St. Joseph Hospital. The datasets contain information about their standard pricing for their hospital services.
- Data analysis process:
    1. Conducted summary statistics for both datasets. For columns with numerical data, I calculated the count, mean, minimum, maximum, standard deviation, and quartiles. For the columns with catergorical data, I calculated the count, frequency of data, top data, and unique data.
    2. I then created histograms for both datasets. For the New York Presbyterian Hospital dataset, I specifically looked at the "minimum negotiated charges" column. For the St. Joseph Hospital dataset, I specifically looked at the "package size" column.
- How to replicate my SQLite database setup:
    1. Import create_engine by doing 'from sqlalchemy import create_engine'.
    2. Import SQLite by doing 'import sqlite3'.
    3. Using SQLite, create and name your database 'health.db'
    4. Create a table using the SQL command 'CREATE TABLE'. Next to it, name your table 'SJH'.
       a. Create new columns for the table.
       b. Create new rows with data for the table. Use the SQL command 'INSERT INTO SJH'
    5. Create an engine using 'create_engine' to connect to the database.
    6. Turn the table into a pandas dataframe using 'pd.read_sql()'.
