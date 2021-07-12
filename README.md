<h1 align="center"> Data base </h1> <br>

## Table of Contents

- [Introduction](#introduction)
- [This&nbsp;respository](#thisrepository)
- [Dependencies](#dependencies)
- [Platzi&nbsp;Course](#platzicourse)

## Introduction
Database arise from the need to maintain data. Initially the databases were based on files, in which information was stored in plain text. Later, relational algebra arose, from which the databases that use the Structured Query Language (SQL) arose, this changed the data storage paradigm and became the general standard, however, new models of database are coming out which are known as NoSQL.

#### Normalization in SQL
For relational databases, there are a some rules that allow data to be normalized, in order to generate a relational model that can be used by SQL. Briefly these rules are:
1- First normal form (1FN) Repeated fields must be eliminated.
2- Second normal form (2FN) Complies with 1FN and each field in the table must depend on a single key.
3- Third normal form (3FN) Complies with 1FN and 2FN and non-key fields must not have dependencies.
4- Fourth normal form (4FN) Complies with 1FN, 2FN and 3FN, multi-valued fields are identified by a unique key.

#### DDL
Data Definition Language are instructions used at the beginning of a SQL database project. Some of them are:
- CREATE-> creates databases (schemas) and tables
- ALTER-> modifies a schema or table
- DROP-> drops an entire table or schema

#### DML
Data Manipulation Language are instructions that are used more frequently, since they are those that allow to interact with the information contained in the SQL database. Some of the instructions are:
- SELECT -> is used to retrieve data from the database
- INSERT -> is used for inserting a data into a table

#### Non-relational database
Non-relational databases are those that meet specific needs that the SQL model cannot cover, these can be classified as:
- Key-value. They store and extract data quickly thanks to the use of a unique key. Some of the databases of this type are DynamoDB and Cassandra.
- Document-based. They are a key-value implementation that varies in the semi-structured way they treat information, it is ideal for storing JSON and XML data. They are mainly used to keep the state of an application, but they are not very efficient for specific searches such as SQL. Some of the databases of this type are Mongo DB and Firestores.
- Based on graphs. Based on graph theory, they are used for entities that are interconnected by multiple relationships. Ideal for storing complex relationships. Some popular databases of this type are TITAN.
- Memory. Database that stores and consults information quickly, but the information is volatile. Some of the most popular databases are Memcached and Redis.
- Optimized for search. They can be of different structures, their advantage is that complex queries and searches can be done in a simple way, some of this database are Big Query and Elasticsearch.


## This&nbsp;repository
For this course a database was created in MySQL which was replicated in Firestore. The database that was created is based on the following diagram, this image was obtained from MySQL using reverse engineering.

<p align="center">
  <img src = "https://github.com/Guillermosesena/database/blob/main/Images/diagram.png" width=800>
</p>

## Dependencies
- MySQL


## Platzi&nbsp;Course

Check out [Platzi's Database Fundamentals course](https://platzi.com/clases/bd/).
