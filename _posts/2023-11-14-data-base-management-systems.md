---
author: Divyashree vyas
categories: 
- DBMS 
- mysql
- application
- database 
tags: 
- featured 
layout: post
primaryKeywords: []
secondaryKeywords: []
title: Data Base Management Systems
image: /uploads/11_14_2023_1699971626179_1234.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1648&q=80

---

![MySQL](/uploads/11_14_2023_1699971664020_1234.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1648&q=80)
&nbsp;
At the heart of all applications is the database, where all data related to the application is stored.
In a series of posts, I’ll be discussing how database management systems are used in application development.
In this introductory post, I’ll be giving a quick overview of some database terms.
# What is a database management system?
A database management system is software used to properly store, retrieve, and update data in a database. A database is a collection of interrelated data.
A view is a subset of data returned from a query (a query is a request for data from a database). A view hides unnecessary details from users and provides security to prevent users from accessing restricted data.
The structure of data is very important in database management systems. The overall design of a database is called a schema. A schema describes the logical design of a database. Schemas are the blueprint for how the database will be constructed.
The data model is a way to describe your data, relationships in your data, and data consistency and constraints. There are four types of data models:
1. Relation Model
1. Entity-Relationship Model
1. Object-based Data Model
1. Semistructured Data Model
The relationship model and the entity-relationship model are the most widely used data models.
The database system provides a data-definition language that is used to specify the database schema and a data-manipulation language that is used to interact with the database. These are not two separate languages; they form a single database language, such as the widely used SQL (which we will be discussing in a later post).
DBMS needs to ensure data is safe in the event of crashes and against unauthorized access. Since data in applications is usually shared among multiple users, the DBMS must avoid inconsistent results.
Applications often perform multiple operations on the database that count as one unit of work. A transaction must hold the following set of properties:
1. Atomicity
1. Consistency
1. Isolation
1. Durability
These properties guarantee reliability even in the event of errors or power failures. Transactions that are performed concurrently must be executed without conflict.
Data is important to every application. The database can be considered the heart of an application.
In the coming series of posts, I will be going in depth about different database topics, using a well-known application as an example.&nbsp;
