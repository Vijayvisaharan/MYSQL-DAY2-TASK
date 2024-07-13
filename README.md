#MYSQL
-MySQL is an open-source relational database management system (RDBMS) that is widely used for managing and manipulating structured data.
-It falls under the category of relational databases, which means it stores data in tables with predefined schemas, and it supports SQL (Structured Query Language) for querying and managing the data.
-
##SQL Script Explanation
-Each CREATE TABLE statement creates a table with specified columns and constraints. The FOREIGN KEY constraints ensure referential integrity by linking columns to primary keys in other tables.
-
##Understanding the Relationships
users -> students/mentors: A user can be a student or a mentor.
mentors -> topics: Each topic is associated with a mentor.
topics -> tasks: Each task is related to a topic.
users -> attendance: Users attend sessions related to topics.
