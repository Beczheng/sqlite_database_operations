# sqlite_database_operations

### **Assignment**
- Course: HHA 504
- Homework assignment #3: Introduction to the world of databases, starting with SQLite. Integrate data processing with Python, utilize Pandas for exploratory data analysis, and conduct database operations using SQLite.

### **Summary of the assignment**
- Details on the datasets:
    1. Used datasets from New York Presbyterian Hospital and St. Joseph Hospital. The datasets contain information about standard pricing for hospital services.
- Data analysis process:
    1. Conducted summary statistics for both datasets. For the columns with numerical data, I calculated the count, mean, minimum, maximum, standard deviation, and quartiles. For the columns with catergorical data, I calculated the count, frequency, top data, and unique data.
    2. Created histograms for both datasets. For the New York Presbyterian Hospital dataset, I specifically looked at the "minimum negotiated charges" column. For the St. Joseph Hospital dataset, I specifically looked at the "package size" column.
- How to replicate my SQLite database setup:
    1. Import SQLite: `import sqlite3`.
    2. Import create_engine: `from sqlalchemy import create_engine`.
    3. Create a connection object using `sqlite3.connect()`.
    4. Create a cursor object using `.cursor()`.
    6. Create a table with columns using the SQL command `CREATE TABLE <name of table>`. Then, execute it using `execute()`. Make sure to commit the changes using `.connect()`.
    7. Create rows with data for the table. Then, execute it using `execute()`. Make sure to commit the changes using `.connect()`
    8. Insert the rows with data into the table. Use the SQL command `INSERT INTO <name of table>`.
    9. Create an engine using `create_engine` to connect to the database.
    10. Turn the table into a pandas dataframe using `pd.read_sql()`.
    11. Close the connection object and cursor object using `.close()`.
    For more details about the code click [here](https://github.com/Beczheng/sqlite_database_operations/blob/main/HHA_504_HW_3.ipynb)
