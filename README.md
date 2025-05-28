# Intro to Structured Query Language (SQL)
  
**Overview:** A *database* is an organized data source/structure that should be easily accessible (by appropriately authenticated and authorized users, when relevant) for data management, retrieval, and long-term storage. *Relational Database Management Systems (RDBMSes)* are specialized databases that store data in tables (and sometimes other structures, such as forms and queries in Microsoft Access software) and share data between tables using common columns. *Structured Query Language (SQL)* is a standardized language that performs RDBMS tasks such as creating, reading, updating, and deleting data (also known as 'CRUD' operations).
  
#### Table of Contents
  
1. [NoSQL vs. SQL](#no-sql)
2. [CRUD Operations](#crud)
3. [Database Terms](#key-terms)
4. [SQL Clauses](#sql-clauses)
5. [SQL Joins](#sql-joins)
6. [Supplemental Resources](#supplemental)
  
<hr />
    
## 1. <a name="no-sql">NoSQL vs. SQL</a>
  
Several key differences between SQL and Not Only SQL (NoSQL) databases include:

| Feature | SQL | NoSQL |
| :---: | :---: | :---: |
| Direction of Scalability | Vertical | Horizontal |
| Popular Objects | Tables | Column Stores, Documents, Graphs, Key-Value Pairs |
| Schemas | Predefined | Dynamic |
| Transaction Handling | Rows (Single or Multiple) | Unstructured Data (e.g., JSON) |
  
Some common reasons for choosing a NoSQL database include: quick response times/low latency, instant/real-time analytics, constantly-evolving data, and server scalability needs.
  
* **Examples of NoSQL Databases include:**
    - [Actian NoSQL Object Database](https://www.actian.com/databases/nosql/): Supports transactional storage of data using object-oriented programming (OOP) languages.
    - [Apache Cassandra](https://cassandra.apache.org/_/index.html): Optimizes parallel/commodity computing to handle and serve massive data volumes.
    - [Apache HBase](https://hbase.apache.org/): Enables fault-tolerant storage of sparse data.
    - [Couchbase](https://www.couchbase.com/): Promotes linear scalability and memcached key/value data storage.
    - [MongoDB](https://www.mongodb.com/): Utilizes JSON-like documents and handles large volume, diverse data storage (e.g., e-mails, scanned documents).
    - [Redis](https://redis.io/): Popular as a message broker and distributed cache, supporting low-latency reading and writing.
  
<hr />
  
## 2. <a name="crud">CRUD Operations</a>

Persistent storage databases have four types of operations that are performed open them, which are commonly abbreviated as *CRUD*:

| CRUD Principle | Popular SQL Statement Keywords |
| :---: | :---: |
| **C**reate | INSERT INTO/VALUES, CREATE TABLE |
| **R**ead | SELECT |
| **U**pdate | UPDATE, ALTER TABLE/ADD |
| **D**elete | DELETE, DROP TABLE |
  
<hr />
  
## 3. <a name="key-terms">Database Terms</a>
  
**Table:** A database object/structure containing related fields (columns) and their associated records (rows).  
**Field:** A column from a database table. This is a vertical data unit with a name and a data type (e.g., Integer, String, Date).  
**Record:** A row from a database table. This is a horizontal data unit that spans all of the fields (columns) in a table.  
**Entity:** A 'noun' (person, place, or thing) that the data of a record (row) describes.  
  
**Primary Key:** One or more fields (columns) in a database table that uniquely identifies a row by not permitting repeat values (IDs, such as student and employee IDs, are popular primary keys).  
**Foreign Key:** One of more fields (columns) in a database table that only include values corresponding to the primary key of another table. Primary and foreign keys, in tandem, define table relationships.  
**Referential Integrity:** Occurs when the values of a foreign key successfully correspond to the row values of an associated table's primary key.  
  
**Relational:** A database type in which the relationships between tables are established via matching/corresponding fields (columns). A software program that provides data persistence for and manages relational databases is referred to as an *RDBMS* (Relational Database Management System).  
**Normalization:** A data organization approach in which best practices for data integrity are followed (data are consistent and redundancy is reduced).
  
<hr />
  
## 4. <a name="sql-clauses">SQL Clauses</a>  

Six of the most commonly applied SQL clauses include:
  
* **SELECT:** Specifies which column(s) results should be returned from.
* **FROM:** Specifies which table(s) results should be returned from.
* **WHERE:** Filters datas based on provided conditions/constraints.
* **GROUP BY:** Brings together rows (as summary rows) that have the same values for specified columns/fields.
* **HAVING:** After aggregate functions are utilized, filters grouped rows according to provided specifications.
* **ORDER BY:** Sorts data in ascending (A-Z, 0-9) or descending (Z-A, 9-0) order.  
  
<hr />
  
## 5. <a name="sql-joins">SQL Joins</a>
  
An SQL `JOIN` clause combines rows/records from multiple tables, relying on a related column/field from between them in doing so. Types of joins include:
  
**INNER JOIN**: Retrieves records with corresponding values from the tables expressed in the join clause.  
**LEFT OUTER JOIN**: Retrieves all records from the 'left' table, as well as corresponding records from the 'right' table.  
**RIGHT OUTER JOIN**: Retrieves all records from the 'right' table, as well as the corresponding records from the 'left' table.  
**FULL OUTER JOIN**: Retrieves all corresponding records, regardless of if the match is form the 'left' or 'right' table.  
  
<hr />
  
## 6. <a name="supplemental">Supplemental Resources</a>
  
* *[Data Repositories Overview Guide](https://github.com/chaseofthejungle/data-repositories-overview)*  
* *[Types of Databases Guide](https://github.com/chaseofthejungle/types-of-databases)*
* *[Codecademy Learn SQL Course](https://www.codecademy.com/learn/learn-sql)*
  
<hr />
  
**TODO:** Add sections on limits/offsets and constraint operators.
