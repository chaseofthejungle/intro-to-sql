# Intro to Structured Query Language (SQL)
  
**Overview:** A *database* is an organized data source/structure that should be easily accessible (by appropriately authenticated and authorized users, when relevant) for data management, retrieval, and long-term storage. *Relational Database Management Systems (RDBMSes)* are specialized databases that store data in tables (and sometimes other structures, such as forms and queries in Microsoft Access software) and share data between tables using common columns. *Structured Query Language (SQL)* is a standardized language that performs RDBMS tasks such as creating, reading, updating, and deleting data (also known as 'CRUD' operations).
  
#### Table of Contents
  
1. [CRUD Operations](#crud)
2. [Key Terms](#key-terms)
3. [NoSQL vs. SQL](#no-sql)
4. [SQL Clauses](#sql-clauses)
5. [Supplemental Resources](#supplemental)
  
<hr />
  
## 1. <a name="crud">CRUD Operations</a>

Persistent storage databases have four types of operations that are performed open them, which are commonly abbreviated as *CRUD*:

| CRUD Principle | Popular SQL Statement Keywords |
| :---: | :---: |
| **C**reate | INSERT INTO/VALUES, CREATE TABLE |
| **R**ead | SELECT |
| **U**pdate | UPDATE, ALTER TABLE/ADD |
| **D**elete | DELETE, DROP TABLE |
  
<hr />
  
## 2. <a name="key-terms">Key Terms</a>
  
<hr />
  
## 3. <a name="no-sql">NoSQL vs. SQL</a>
  
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
  
## 4. <a name="sql-clauses">SQL Clauses</a>
  
Six of the most commonly applied SQL clauses include:
  
* **SELECT:** Specifies which column(s) results should be returned from.
* **FROM:** Specifies which table(s) results should be returned from.
* **WHERE:** Filters datas based on provided conditions/constraints.
* **GROUP BY:** Brings together rows (as summary rows) that have the same values for specified columns/fields.
* **HAVING:** After aggregate functions are utilized, filters grouped rows according to provided specifications.
* **ORDER BY:** Sorts data in ascending (A-Z, 0-9) or descending (Z-A, 9-0) order.
  
<hr />
  
## 5. <a name="supplemental">Supplemental Resources</a>
  
* *[Data Repositories Overview Guide](https://github.com/chaseofthejungle/data-repositories-overview)*  
* *[Types of Databases Guide](https://github.com/chaseofthejungle/types-of-databases)*
* *[Codecademy Learn SQL Course](https://www.codecademy.com/learn/learn-sql)*
  
<hr />
  
TODO: 'Key Terms' (column/field, row/record, entity, table, primary key, foreign key, relational, RDBMS, referential integrity, normalization, inner join, outer join) section content.
