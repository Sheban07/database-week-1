# database-week-1

1. A DBMS is a software system that uses a standard method to store and organize data. The main components of a DBMS are:

- Database Engine: This is the core service for accessing and processing the data stored in the database.
- Database Schema: This defines the logical structure of the database, including tables, views, and indexes.
- Query Processor: This component interprets and executes database queries.
- Transaction Manager: Ensures data consistency and handles transactions (a sequence of operations performed as a single logical unit of work).
- Storage Manager: Manages the storage of data, both in memory and on disk.



2. Relational Database and Examples
- A relational database is a type of database that stores data in tables (or relations). Each table consists of rows and columns, where rows represent records and columns represent attributes.

**Examples**
- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server

3. 
- DDL (Data Definition Language): Deals with database schemas and descriptions. Examples include CREATE, ALTER, DROP.
- DML (Data Manipulation Language): Deals with data manipulation. Examples include SELECT, INSERT, UPDATE, DELETE.
- DCL (Data Control Language): Deals with rights, permissions, and other controls. Examples include GRANT, REVOKE.

4. 
- Primary Key: A unique identifier for a record in a table. It must contain unique values and cannot contain NULL values.
- Foreign Key: A field (or a collection of fields) in one table, that uniquely identifies a row of another table. This key creates a relationship between the two tables.

5. 
- An Entity-Relationship Diagram  is a visual representation of the entities in a database and the relationships between them. It helps in designing the database structure and understanding the data flow. 

6. 
- Simplicity: Use a straightforward tabular structure.
- Data Integrity: Ensures accuracy and consistency through constraints.
- Flexibility: Easily modify schema without impacting existing data.
- Scalability: Handle large volumes of data effectively.
- Security: Robust access control and permissions.

7. 
- INT: Integer data type for storing whole numbers.
- VARCHAR: Variable character data type for storing strings of variable length.
- DATE: Data type for storing dates.
- FLOAT: Floating-point number data type for storing numbers with decimals.

8. 
- The primary purpose of a DBMS is to provide a way to store, retrieve, and manage data efficiently and securely. Key benefits include:
- Data Abstraction and Independence: Simplifies data manipulation.
- Data Security: Protects data from unauthorized access.
- Data Integrity: Maintains accuracy and consistency of data.
- Concurrency Control: Allows multiple users to access data concurrently.
- Backup and Recovery: Ensures data can be restored in case of failures.
