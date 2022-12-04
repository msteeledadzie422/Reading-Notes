# nosql vs sql

_1. What type of database is the best fit for the complex query intensive environment?_

    SQL databases are a good fit for the complex query intensive environment whereas NoSQL databases are not a good fit for complex queries. At a high level, NoSQL does not have standard interfaces to perform complex queries, and the queries themselves in NoSQL are not as powerful as the SQL query language.

_2. What type of database is the best fit for hierarchical data storage?_

    NoSQL databases fit better for hierarchical data storage as it follows the key-vlue pair way of storing data similar to JSON data. NoSql databases are highly preferred for large datasetse.

_3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend._

    In most situations, SQL databases are vertically scalable. You can manage increasing loads of data by increasing the CPU, RAM, SSD, etc. on a single server. On the other hand, NoSQL databases are horizontally scalable. You can add new servers easily in your NoSQL database infrastructure to handle large traffic.


# sql modeling techniques

_1. Among data tables, what is a one-to-many relationship and how do we “relate” them?_

    A one-to-many relationship is when an entry in one table is related to more than one entry in another. These are related by connecting lines between two tables to show relationships.

_2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships._

    During the design process, it is often usesful to create diagrams of the databse tables and their relationships. 

_3. Explain the difference between a primary and foreign key._

    A Primary Key uniquely identifies each row in a table. A table typically has one primary key, but can have more. When the key has more than one column, it is called a compound key.
    
    A Foreign Key is a column or set of columns which match a primary key in another table.

# sql vs nosql

_1. How do we treat keywords and parameters differently in SQL syntax?_

    We use SQL syntax/keywords to identify what data/parameters we would like to retreive which which database(s).

_2. Define normalization within the context of schemas and data._

    Normalization ensures that, whenever we are fetching our data we structure any data entering a table into the format needed for that table.

_3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter._

    A  one-to one relationship is when one entry in a table is related to one entry in another table.
    
    A one-to-many relationship is when one entry in a table is related to multiple entries in another table or other tables.
    
    A many-to-many relationship creates an additional table to create relationships between multiple tables. 
    
