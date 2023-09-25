# sqlite_database_operations
HHA 504 - Week 3 

Homework assignment #3: Introduction to the world of databases, starting with SQLite. Integrate data processing with Python, utilize Pandas for exploratory data analysis, and conduct database operations using SQLite.

**Summary:**
- Details on the datasets:
    1. Used datasets from New York Presbyterian Hospital and St. Joseph Hospital. The datasets contain information about standard pricing for hospital services.
- Data analysis process:
    1. Conducted summary statistics for both datasets. For columns with numerical data, I calculated the count, mean, minimum, maximum, standard deviation, and quartiles. For the columns with catergorical data, I calculated the count, frequency, top data, and unique data.
    2. Created histograms for both datasets. For the New York Presbyterian Hospital dataset, I specifically looked at the "minimum negotiated charges" column. For the St. Joseph Hospital dataset, I specifically looked at the "package size" column.
- How to replicate my SQLite database setup:
    1. Import create_engine: `from sqlalchemy import create_engine`.
    2. Import SQLite: `import sqlite3`.
    3. Using SQLite, create and name your database `health.db`.
    4. Create a table using the SQL command `CREATE TABLE`. Next to it, name your table `<name of table>`.
       - Create new columns for the table.
       - Create new rows with data for the table. Use the SQL command `INSERT INTO <name of table>`.
    5. Create an engine using `create_engine` to connect to the database.
    6. Turn the table into a pandas dataframe using `pd.read_sql()`.

       For more information about the code click [here](https://github.com/Beczheng/sqlite_database_operations/blob/main/HHA_504_HW_3.ipynb)
