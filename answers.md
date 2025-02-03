1. Components of a DBMS (Database Management System):

Hardware: Physical devices like the computer or server that runs the DBMS software.
Software: The DBMS software itself which manages data, provides interfaces, and ensures database operations.
Data: The actual data that the DBMS is managing, which is organized in tables, views, and other structures.
Procedures: Instructions and protocols that define how the database is used, managed, and manipulated.
Database Access Language (DAL): A language used by users and applications to interact with the database (e.g., SQL).
Users: Individuals who interact with the DBMS, such as administrators, developers, and end-users.

2. What is a Relational Database? Give 4 Examples: A relational database is a type of database that stores data in tables (also called relations) and defines relationships between the tables using keys (primary and foreign keys). Data is organized in rows and columns, and the relationships are established using a set of rules (e.g., normalization).

Examples:
MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
Three Classifications of SQL: SQL (Structured Query Language) can be classified into three major categories:

3. Data Query Language (DQL): Used to query the database and retrieve data (e.g., SELECT statement).
Data Definition Language (DDL): Defines the structure of the database, such as creating or altering tables (e.g., CREATE, ALTER, DROP statements).
Data Manipulation Language (DML): Allows users to manipulate data within the tables (e.g., INSERT, UPDATE, DELETE statements).
Difference Between a Primary Key and a Foreign Key:

4. Primary Key: A primary key is a unique identifier for each record in a table. It ensures that no two rows can have the same value for the primary key.
Example: In a Student table, the student ID could be a primary key.
Foreign Key: A foreign key is a field in one table that uniquely identifies a row of another table. It creates a relationship between two tables by referencing the primary key of another table.
Example: In an Enrollment table, the student_id could be a foreign key referring to the student_id in the Student table.

5. What is an Entity-Relationship Diagram (ERD)? An Entity-Relationship Diagram (ERD) is a visual representation of the relationships between entities in a database. It shows how data entities (tables) are related and the attributes of each entity. It helps in designing and structuring a database by visually illustrating the entities and their relationships.

6. Advantages of Relational Databases:
Data Integrity: The use of primary and foreign keys helps maintain data consistency and accuracy.
Flexibility: Relational databases can handle a wide variety of data and adapt to changes in business requirements.
Ease of Use: SQL provides a standardized and simple language to interact with the database.
Security: Role-based access control ensures that sensitive data is protected and accessible only to authorized users.
Four Types of Data Types Used to Store Data in Tables:

7. 
Integer (INT): Used to store whole numbers.
Varchar (VARCHAR): Used to store variable-length strings of characters.
Date (DATE): Used to store date values.
Boolean (BOOLEAN): Used to store true/false values.

8. Purpose of a Database Management System (DBMS): The purpose of a DBMS is to provide an efficient, secure, and organized way to store, retrieve, and manage data. It helps users easily create and maintain databases, while providing tools for data manipulation, security, backup, and recovery. A DBMS simplifies data management, enforces consistency, and ensures data integrity while supporting concurrent access by multiple users.