---
author: Programmingera
categories: []
tags: []
layout: post
primaryKeywords: []
secondaryKeywords: []
title: Database Management Systems For Application Development
image: /uploads/14_11_2023_1699972890165_file.png

---

![database server](/uploads/14_11_2023_1699972897582_file.png)
At the heart of all application is the database where all data related to the application is stored.
In a series of posts I’ll be discussing how Database Management Systems are used in applications development.
In this introductory post I’ll be giving a quick overview of some Database terms.
# Whats is a Database Management Systems?
A Database Management Systems is a software used to properly store, retrieve and update data in a database. A database is a collection of interrelate data.
A view is a subset of data returned from a query (A query is a request for data from a database). A view hides unnecessary details away from users and provide security to prevent users from accessing restricted data.
The structure of data is very important in database management systems. The overall design of a database is called a Schema. Schema describes the logical design of a database. Schemas are the blueprint of how the database will be constructed.
The data model is a way to describe your data, relationships in your data and data consistency and constraints. There are four type of data models:
1. Relation Model
1. Entity-Relationship Model
1. Object-based Data Model
1. Semistructured Data Model
The Relation Model and the Entity-Relationship Model are the most widely used data models.
Database System provides a data-definition language that is used to specify the database schema and a data-manipulation language that is used to interact with the database. These are not two separate languages, they form a single database language, such as the widely used SQL (Which we will be discussing in a later post).
DBMS needs to ensure data is safe in the event of crashes and against unauthorized access. Since data in application are usually shared among multiple users, the DBMS must avoid inconsistent result.
Application often perform multiple operations on the database that count as one unit of work. Transaction must hold the following set of properties:
1. Atomicity
1. Consistency
1. Isolation
1. Durability
These properties guarantees reliability even in the event of errors or power failure.Transactions that are performed concurrently must be executed with out conflict.
Data is important to every application. The database can be considered the heart of an application.
In the coming series of posts I will be going in depth about different database topics using a well-know application as an example.
