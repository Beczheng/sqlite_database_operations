# sqlite_database_operations

### Assignment
- Course: HHA 504
- Homework assignment #3: Introduction to the world of databases, starting with SQLite. Integrate data processing with Python, utilize Pandas for exploratory data analysis, and conduct database operations using SQLite.

### Summary of the assignment
#### 1. Details on the datasets:
- Used datasets from New York Presbyterian Hospital and St. Joseph Hospital. The datasets contain information about standard pricing for hospital services.
#### 2. Data analysis process:
- Conducted summary statistics for both datasets. For the columns with numerical data, I calculated the count, mean, minimum, maximum, standard deviation, and quartiles. For the columns with catergorical data, I calculated the count, frequency, top data, and unique data.
- Created histograms for both datasets. For the New York Presbyterian Hospital dataset, I specifically looked at the "minimum negotiated charges" column. For the St. Joseph Hospital dataset, I specifically looked at the "package size" column.

### Steps to replicate my assignment
#### 1. Import the following:
- Import SQLite: `import sqlite3`.
- Import create_engine: `from sqlalchemy import create_engine`.
#### 2. Create the following: 
- Create a connection object using `sqlite3.connect(<'name of database'>)`.
- Create a cursor object using `.cursor()`.
- Create a new table with columns using the SQL command `CREATE TABLE <name of table>`. Then, execute it using `execute()`. Make sure to commit the changes using `.commit()`.
- Create and insert new rows with data into the table using the SQL command `INSERT INTO <name of table>`. Then, execute it using `execute()`. Make sure to commit the changes using `.commit()`
- Turn the table into a pandas dataframe using `pd.read_sql()`.
#### 3. Close the following: 
- Close the connection and cursor using `.close()`.
For more details about the code click [here](https://github.com/Beczheng/sqlite_database_operations/blob/main/HHA_504_HW_3.ipynb)
