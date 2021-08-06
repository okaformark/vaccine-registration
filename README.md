# vaccine-registration

# Introduction
An object-relational database (ORD) is a database management system (DBMS) that’s composed of both a relational database (RDBMS) and an object-oriented database (OODBMS).
ORD supports the basic components of any object-oriented database model in its schemas and the query language used, such as objects, classes and inheritance.
A hybrid database or Object-relational database it supports and uses both on-disk and in-memory data storage. Hybrid databases are used when the system needs high performance with the small footprint that only in-memory database systems can provide. This also provides the added benefits of durability and low cost of disk-based database systems. In short, the system makes use of hard disks for saving and retaining data, yet makes use of the memory for data that is in dynamic use to increase performance.

COVID- 19 VACCINE REGISTRATION DATABASE PROJECT was inspired on the current situation of spread of this pandemic disease, Although the vaccine has been administered but
majority of people especially youth seems not able to register due to busy daily life schedule. This project will enable individual to set their vaccine appointment at their preferred time so as many people could get vaccinated as soon as possible. The database is designed with fundamentals of Object-Relational database in which we use
SQLAlchemy as the Python SQL toolkit and Object Relational Mapper that gives us the full power and flexibility of SQL since the ORM provided by SQLAlchemy sits between the SQLite database which is for storage and Python program and transforms the data flow between the database engine and Python objects.
Main primary users include Patient and vaccine administer. In our database all objects created include, Patient profile, Patient personal information address, type of vaccine requested, dates for appointment, site location, vaccine administer information will be able to be stored and retrieved when needed using Data Manipulation Language.

# Methodology

## Database schema
A database schema is the skeleton structure that represents the view of the entire database. It defines how the data is organized and how the relations among them are associated. It formulates all the constraints that are to be applied on the data. In this project we based on Logical Database Schema which defines all the logical constraints that applied on the data stored. Since we use Object-Relational database mechanisms, we created 11 Classes and its attributes which have functions or methods that’s allow a user to put or access the objects stored.

## E-R diagram
An entity relationship diagram (ERD) shows the relationships of entity sets stored in a database.
An entity in this context is an object, a component of data. An entity set is a collection of similar entities. These entities can have attributes that define its properties. In this project, ER diagrams symbols are used to elaborate the relationship of classes including using primary key
and foreign key.

## Data definition or Data description language (DDL)
Is a syntax for creating and modifying database objects such as tables, indices, and users. DDL
statements are similar to a computer programming language for defining data structures, especially database schemas. In This project the syntax for table creation, data integrity constraints,table altering, and updating features will be illustrated.

