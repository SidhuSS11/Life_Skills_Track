# Structured Query Language (SQL)

Structured Query Language (SQL) is a standard language used for relational database management systems (RDBMS). SQL has been in use since the 1970s and is widely used for managing and querying data. SQL is a declarative language that allows users to define what data they want to retrieve and how the data should be organized.

### SQL Overview:

SQL is a domain-specific language that is used to manage relational databases. SQL allows users to create and manipulate tables, add and delete data, and perform queries to retrieve data. SQL is made up of three main components: data definition language (DDL), data manipulation language (DML), Data Query Language (DQL), Transaction Control Language (TCL) and data control language (DCL).

- DDL allows users to create and modify the structure of a database. This includes creating tables, indexes, and constraints. DDL statements include CREATE, ALTER, and DROP.

- DML allows users to manipulate the data within a database. This includes inserting, updating, and deleting data. DML statements include INSERT, UPDATE, and DELETE.
- DQL is a subset of SQL that is used to retrieve data from a database. The SELECT statement is the most commonly used statement in DQL.

- DCL allows users to control the access and permissions to a database. This includes granting and revoking access, as well as creating and managing users and roles. DCL statements include GRANT and REVOKE.


- TCL, or Transaction Control Language, is a subset of SQL that is used to manage transactions in a database. Transactions are a group of operations that are executed together as a single unit.
- TCL provides users with the ability to control transactions and ensure data integrity. There are three primary statements in TCL: COMMIT, ROLLBACK, and SAVEPOINT.

### SQL Syntax:

SQL syntax is similar to other programming languages. SQL statements are made up of keywords, clauses, and expressions. Keywords are reserved words that have a specific meaning in SQL, such as SELECT, FROM, WHERE, and ORDER BY. Clauses are used to define specific conditions or actions in SQL statements, such as WHERE and GROUP BY. Expressions are used to evaluate and return values, such as arithmetic operations or string concatenation.

### SQL Data Types:

SQL supports several data types for storing and manipulating data. The most common data types include:

- Numeric: INT, FLOAT, DOUBLE, DECIMAL
- String: CHAR, VARCHAR, TEXT
- Date/Time: DATE, TIME, DATETIME
- Boolean: BOOLEAN
### SQL Constraints:

SQL constraints are used to enforce rules on the data in a database. Constraints can be added to tables during the DDL process. Some common constraints include:

- Primary Key: A unique identifier for a record in a table
- Foreign Key: A reference to a primary key in another table
- Not Null: Ensures a value is not null
- Unique: Ensures a value is unique within a column

### SQL Joins:
SQL joins are used to combine data from two or more tables based on a related column. The most common types of joins include:

- Inner Join: Returns only the matching records from both tables
- Left Join: Returns all records from the left table and matching records from the right table
- Right Join: Returns all records from the right table and matching records from the left table
- Full Join: Returns all records from both tables, with null values for non-matching records

### Conclusion:
SQL is a powerful language used for managing and querying data in relational databases. SQL is easy to learn and widely used in many industries. SQL syntax and data types are similar to other programming languages, making it easy for developers to learn. SQL constraints and joins provide a way to enforce rules and combine data from multiple tables. SQL continues to be an essential tool for managing and analyzing data in today's data-driven world.

### resources
- https://www.geeksforgeeks.org/sql-ddl-dql-dml-dcl-tcl-commands/
