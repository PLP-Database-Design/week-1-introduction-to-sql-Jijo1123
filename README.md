# SQL Assignment Week 1


Assignment Questions

1. State and Explain the components of a DBMS(Database Management System)

Database Management System (DBMS) consists of the following components:

a. Database Engine: Handles data storage, retrieval, and updates.
b. Database Schema: Defines the structure and organization of data.
c. Query Processor: Interprets and executes user queries.
d. Data Manager: Manages data integrity, security, and transactions.
e. User Interface: Enables interaction with the database.

2. What is a relational database? Give 4 examples.

A relational database organizes data into tables (called relations) consisting of rows (records) and columns (attributes).
It uses Structured Query Language (SQL) for defining, manipulating, and querying the data. 
Relationships between tables are established using primary and foreign keys.

Examples of Relational Databases:
a. MySQL: Open-source and widely used for web applications.
b. PostgreSQL: Advanced open-source database known for extensibility and standards compliance.
c. Oracle Database: A commercial RDBMS used in enterprise applications.
d. Microsoft SQL Server: A proprietary database for enterprise and business applications.

3. State and Explain three classifications of SQL?

A. Data Definition Language (DDL):
Defines and modifies database structures. Examples:

CREATE (creates tables, schemas), ALTER (modifies existing structures) and DROP (deletes tables or databases)

Data Manipulation Language (DML)Handles data retrieval and modification. Examples:

SELECT (retrieves data), INSERT (adds records), UPDATE (modifies records) and DELETE (removes records).

Data Control Language (DCL):
Manages user permissions and access. Examples:

GRANT (gives permissions) and REVOKE (removes permissions).

4. What is the difference between a Primary Key and a Foreign Key?

A Primary Key uniquely identifies each record in a table and must contain unique, non-null values.
A Foreign Key is a field in one table that references the Primary Key in another table, establishing a relationship 
between the two tables. The Primary Key ensures uniqueness; the Foreign Key enforces referential integrity.

5. What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a visual representation of entities, their attributes, and relationships in a database. 
It helps design and organize data structures for relational databases.

6. What are the advantages of relational databases?

Advantages of Relational Databases:  
- Data Integrity: Maintains accuracy and consistency.  
- Flexibility: Supports complex queries using SQL.  
- Scalability: Handles large datasets efficiently.  
- Data Relationships: Establishes connections via primary and foreign keys.  
- Standardization: Follows widely accepted design principles.

7. State four types of data type used to store data in tables?

Four types of data types used in tables:  
1. Integer: Stores whole numbers.  
2. Varchar: Stores strings or text.  
3. Date/Time: Stores date and time values.  
4. Boolean: Stores true/false values.  
   
8. What is the purpose of a database management system (DBMS)?  

The purpose of a Database Management System (DBMS) is to efficiently store, retrieve, and manage data in a structured manner. 
It ensures data consistency, security, and integrity while allowing users to query, update, and manipulate data through an interface. 
It simplifies data management for applications and users.

