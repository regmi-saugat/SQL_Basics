## Database: 
A database is a shared collection of logically related data and description of these data, designed to meet the information needs of an organization.

**Usages of Database:** 
- Data Storage: A database is used to store large amounts of structured data, making it easily accessible, searchable, and retrievable. 
- Data Analysis: A database can be used to perform complex data analysis, generate reports, and provide insights into the data. 
- Record Keeping: A database is often used to keep track of important records such as financial transactions, customer information, and inventory levels. 
- Web Applications: Databases are an essential components of many web applications, providing dynamic content and user management. 


**Properties of an Ideal Database:**
- Integrity (Accurate and Consistent)  
- Availability 
- Security 
- Independent of Application 
- Concurrency 


**Types of Database:**
- Relational Database: Also known as SQL databases, these databases use a relational model to organize data into tables with rows and columns. ( MySQL, Oracle, Microsoft Access, PostgreSQL) 
- NoSQL Database: These databases are designed to handle large amounts of unstructured of unstructured or semi-structured data, such as documents, images, or videos. (MongoDB) 
- Column Database: These databases store data in columns rather than rows, making them well suited for data warehousing and analytical applications. (Amazon Redshift, Google Big Query )
- Graph Database: These databases are used to store and query graph-structured data, such as social network connections or recommendation systems. ( Neo4j, Amazon Neptune )
- Key - value Database: These databases stores data such as keys and values, making well-suited for caching and simple data storage needs. ( Redis, Amazon DynamoDB )

-----

**Database Management System:** A database management system is a software system that provides the interfaces and tools needed to store, organize, and manage data in a database. A DBMS acts as an intermediary between the database and the applications or users that access the data stored in the database.

**Core Functionalities of DBMS:**
  - Data Management: store, retrieve and modify data 
  - Integrity: Maintain accuracy of data 
  - Concurrency: Simultaneous data access for multiple users 
  - Transaction: Modification to database must either be successful or must not happen at all 
  - Security: Access to authorized users only  
  - Utilities: Data import/export, user management, backup, logging 

**Database Keys:** A key in a database is an attribute or a set of attributes that uniquely identifies a tuple(row) in a table. Keys plays a crucial role in ensuring the integrity and reliability of a database by enforcing unique constraints on the data and establishing relationships between tables. 

| Roll No. | Name | Branch | Email | 
| ----- | -----| ----- | -----|
| 1 | Alish Sharma | CSE | sharmaalish65@gmail.com |
| 2 | Saugat Regmi | BCA | regmisaugat1602@gmail.com | 

## Different types of database keys:

- **Super Key:** A super key is a combination of columns that uniquely identifies any row within a relational database management system(RDBMS) table. 
- **Candidate Key:** A candidate key is a minimal Super Key, meaning it has no redundant attributes. In other words, it's the smallest set of attributes that can be used to uniquely identify a tuple(row) in the table. 
- **Primary Key:** A primary key is a unique identifier for each tuple in the table. There can only be one primary key in a table, and it cannot contain null values.  
- **Alternate Key:** An alternate key is a candidate key that is not used as the primary key. 
- **Composite Key:** A composite key is a primary key that is made of two or more attributes. Composite  key is used when a single attribute is not sufficient to uniquely identify a tuple in a table. 
- **Surrogate Key:** A surrogate key also known as synthetic primary key in a database is a unique identifier for either an entity in the modeled world or an object in a database. This column is used as an identifier for each row rather than relying on pre-existing attributes. 
- **Foreign Key:** A foreign key is a primary key from one table that is used to establish a relationship with another table. 

## Cardinality of Relationship: 
Cardinality in database relationships refers to the number of occurrences of an entity in a relationship with another entity. Cardinality defines the number of instances of one entity that can be associated with a single instance of the related entity. 

Examples:
  - The driving license of a person is a one-to-one relationship
  - The college branch of a student is example of one-to-many relationship
  - The online courses enrolled by the students is the example of many-to-many relationship

## Drawback of Database: 
- **Complexity:** Setting up and maintaining a database can be complex and time-consuming, especially for large and complex systems. 
- **Cost:** The cost of setting up and maintaining a database, including hardware, software, and personnel, can be high 
- **Scalability:** As the amount of data stored in a database grows, it can become more difficult to manage, leading to performance and scalabltiy issues. 
- **Data Integrity:** Ensuring the accuracy and consistency of data stored in a database can be challenge, especially when multiple users are updating the data simultaneously.
- **Security:** Securing a database from unauthorized access and protecting sensitive information can be difficult, especially with the increasing threat of cyber-attacks. 
- **Data Migrations:** Moving data from one database to another or upgrading to a new database can be complex and time-consuming process. 
- **Flexibility:** The structure of a database is often rigid and inflexible, making it difficult to adapt to changing requirements or to accommodate a new types of data. 
