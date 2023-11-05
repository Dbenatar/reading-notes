# MongoDB and Mongoose

SQL:
SQL databases are table based.
Primarily called as Relational Databases.
Have a predefined schema.
Vertically scalable by increasing the horse-power of the hardware.
Use _Structured Query Language_ for defining and manipulating the data.

NoSQL:
NoSQL databases are document based.
Primarily called as non-relational or distributed database.
Have a dynamic schema for unstructured data.
Scaked by increasing databases servers in the pool of resouces to reduce the load.
Queries are focused on collection of documents. Sometimes called as _Unstructured Query Language_.

What kind of data is a good fit for an SQL database?
Data which is represented in the form of a table which consists of a number of rows.

Give a real world example.
An example of this would be a file compliled of your monthly food payments to analyze buying patterns.

What kind of data is a good fit a NoSQL database?
The best fit for a NoSQL database storage is hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.
Give a real world example.
An example of NoSQL database storage is the managing session information. Managing session information for each user who visits a website.

Which type of database is best for hierarchical data storage?
A NoSQL database would be best for hierarchical data storage.

Which type of database is best for scalability?
It would depend on the scale, SQL databases are vertically scalable. Meaning you can increase the load by increasing the hardware power, such as CPU, RAM or SSD. As NoSQL databases are horizontally scalable, you can just add more servers to the database infrastructure to handle the increase of traffic.

What does SQL stand for?
_Structured Query Language_

What is a relational database?
A database structred to recognise relations between stored items of information.

What type of structure does a relational database work with?
This is best suited to a SQL database.

What is a ‘schema’?
A list of logical structures of data or a separate space or container used to handle database files.
What is a NoSQL database?
Databases that store data in any format other than relational tables.

How does it work?
As queries dont have to access serveral tables to deliver an answer, these databases tend to perform faster compared to relational databases. NoSQL databases are most effective for organising and managing large quantities of complex and diverse types of data where the data structure is constantly changing.
What is inside of a MongoDB database?
Unlike a table found in an SQL database, a MongoDB database is made up of collections, which contains documents. These could be looked at like a the rows of a table but made up of a similar format to JSON.
Which is more flexible - SQL or MongoDB? and why.
A SQL databases schema-based approach may hinder its flexibilty in evolving applications, especially those that handle diverse data types. Because of this a MongoDB database would probably be more flexible. The schema-less data model allwos for easy adaptation.
What is the disadvantage of a NoSQL database?
There are a number of disadvantages to a NoSQL database. They have limitationswith multi-document transactions compared to tradional relational databases. The flexible data model can consume more storage space, caching and indexing may lead to increased resource usage.
