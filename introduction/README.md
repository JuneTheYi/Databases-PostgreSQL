# Introduction
#

#### Basics
- Types of DBs
	- flat files (like excel sheets)
	- Document Model Databases (NoSQL)
	- Relational DBs (PostgreSQL)
- RDBMS
	- Relational Database Management Systems
	- MySQL, Oracle, PostgreSQL, etc
- Database Tables
	- Tables contain columns (fields) and rows of data (records)
	- Each column has a defined data type which defines what type of data can be contained within that column
	- Each row of data should be unique
	- Each column should contain only one value per row
	- tables are linked through primary keys and foreign keys
- Data Types
	- Numeric:
		- INT - Whole Numbers
		- NUMERIC(P,S) - Decimals, P = Max number of digits, S = # of digits after decimal
		- SERIAL - Auto incrementing whole numbers, commonly used with ID #s
	- String:
		- CHAR(N) - Fixed length string of length N
		- VARCHAR(N) - Varying length string of max length N
		- TEXT - Varying length string with no max
	- Time:
		- TIME - HH:MM:SS
		- DATE - YYYY-MM-DD
		- TIMESTAMP - YYYY-MM-DD HH:MM:SS
	- BOOLEAN - True or False
	- ENUM - a list of values input by the user. e.g. gender or days of the week
- Primary Keys
	- 1 primary key per table
	- a column which uniquely identifies a record in a table
	- must be unique and cannot be null
- Foreign Keys
	- column where values match the values of another tables primary key column
	- table with primary key is called the reference/parent
	- table with foreign key is called the child table
- Constraints
	- Unique constraint - ensures only unique values, throws an error if duplicate
	- Not null constraint - ensures that NULL values cannot be inserted
	- Check constraint - used to check whether values satisfy a specific boolean expression (e.g. an age column must contain values > 0)

