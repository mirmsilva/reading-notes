# Day 11 Reading Notes

## Data Models (Review the DB Schema)

- You can customize the data model by using attributes that specify formatting, validation, and database mapping rules.

## DBMS

- **Database** is a collection of related data and data is a collection of facts and figures that can be processed to produce information.
- **Database management system** stores data in such a way that it becomes easier to retrieve, manipulate, and produce information.

## Do some research on what a Database Schema is.

- What is a Schema?
  - a structure that dictates how data should be organized and the relationship between data
- Why do we use them?
  - They helps us visualize how data is connected and keep data organized
- What do they look like?
  - Tables
- 
## What are the different types of Database Keys?

- What is a Primary Key?
  - A primary key is an Int ID used as a unique identifier to help parse data
- What is a Foreign Key?
  - A foreign key provides a link between data in two tables and always references a primary key
- What is a Composite Key?
  -  When you combine two or more keys. On their own they don't work
- How are they different? When do you use 1 over the others?
- 
## What are Relationships in a relational database?

- What is a 1:1 relationship?
  - each primary key relates to only one record. The tables only have one record on each side of the relationship
- What is a Many:Many relationship?
  - the primary key table contains one or many records in the related table
- How about a 1: Many or a Many:1?
  - each record in both tables can relate to none or any number of records in the other table. These relationships usually require a third table

### Things I Want To Know More About:


### My Sources:
- https://docs.microsoft.com/en-us/aspnet/core/data/ef-mvc/complex-data-model?view=aspnetcore-2.0
- https://www.tutorialspoint.com/dbms/dbms_overview.htm
- https://www.techopedia.com/definition/7272/foreign-key

[Back to Main](README.md)
