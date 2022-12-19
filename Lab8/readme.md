# Data, Information and Knowledge 
Data is raw, unprocessed facts. It can be numbers, words, images, or sounds, among other things. Data by itself doesn't have much meaning or context.
Information is data that has been processed and organized in a way that gives it meaning and context. Information is useful because it can be used to answer questions, solve problems, or make decisions. Knowledge is understanding and familiarity with a subject or skill, gained through experience or education. It is the combination of information and the understanding of how to use that information to make informed decisions and take appropriate action.
The primary key in the customers table would be a unique identifier for each customer, such as a customer ID number. The primary key in the orders table would be a unique identifier for each order, such as an order number.

The customers and orders tables would be related through the use of a foreign key in the orders table. The foreign key would be the customer ID from the customers table, and it would be used to link each order to the customer who placed it.

For example, if a customer with the ID number 123 placed an order, the orders table might have an entry with the order number 4567 and the foreign key 123, indicating that order 4567 was placed by customer 123. This allows the database to store and retrieve information about both customers and orders in a structured and organized way, and to easily retrieve all of the orders placed by a particular customer by using the customer's ID as a key.

It is important to properly define the data type of a field in a database table because the data type determines what kind of data can be stored in that field, as well as how the data will be processed and used.

# Big Data
The four "Vs" of big data are volume, variety, velocity, and veracity. These characteristics refer to the challenges and opportunities associated with managing and analyzing large amounts of data.
Volume refers to the sheer size of the data. Big data often involves very large datasets that can be difficult to store, process, and analyze using traditional methods.
Variety refers to the different types and formats of data that are included in a big data set. Big data can include structured data, such as numbers and text in a spreadsheet or database, as well as unstructured data, such as images, audio, and video.
Velocity refers to the speed at which data is generated and needs to be processed. In some cases, data must be analyzed in real-time, as it is being generated.
Veracity refers to the quality and reliability of the data. In a big data set, there may be errors, inconsistencies, or missing data that need to be cleaned and checked before the data can be analyzed.
The proliferation of connected devices, such as smartphones, smart watches, and Internet of Things (IoT) devices, which generate vast amounts of data as they communicate with each other and with online servers.

# Structured Query Language 
RDBMS stands for Relational Database Management System. It is a type of database management system that organizes data into tables (also called relations) and allows users to create relationships between these tables using primary and foreign keys.

SQL (Structured Query Language) is a programming language used to manage and manipulate data stored in RDBMS. SQL is used to create, modify, and query relational databases, as well as to control access to the data.

The purpose of SQL is to provide a standard way of interacting with RDBMS and to allow users to easily retrieve, manipulate, and update data stored in a database. SQL includes a wide range of commands and functions that can be used to perform a variety of tasks, such as creating and modifying database tables, inserting and updating data, and querying the database for specific information.

# SQL Injections 
SQL injection is a type of cyber attack that involves injecting malicious code into a website or application through user input fields. The code is written in SQL, the programming language used to manage and manipulate data stored in relational database management systems (RDBMS).

SQL injection attacks are a security threat because they allow attackers to gain unauthorized access to a database, steal sensitive information, or manipulate or delete data. They can also be used to take control of a website or application, or to perform other malicious actions.

One way to reduce the issue is by enforcing strong passwords and using secure authentication: Using strong, unique passwords and implementing secure authentication methods can help to prevent unauthorized access to a database.

