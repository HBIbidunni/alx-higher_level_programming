# SQL - Introduction :eight_spoked_asterisk:
---------
This is an introduction to the __ALX__ Project: __Structured Query Language(SQL)__. 

Here, the key focus of this project centers on: 
- What a __relational database__ is, and its usage.
- How to create a __database__ in __MySQL__, 
- What __Data Definition Language (DDL)__ is. 
- What __Data Manipulation Language(DML)__ is, 
- How to __CREATE__ or __ALTER__ a table,
- How to __SELECT__ data from a table, 
- How to __INSERT__, __UPDATE__ or __DELETE__ data,
- What are __subqueries__ and generally how to use __MySQL__ functions.

### Project Requirements :scroll::ballot_box_with_check:
- All files should be executed on __Ubuntu 20.04 LTS__ using __MySQL 8.0__ (`version 8.0.25`).
- All __SQL queries__ should have a comment.
- All files should start by a comment describing the task.
- All __SQL__ keywords should be in uppercase (`SELECT`,`UPDATE`,`WHERE`…).


__For instance__: A sample on how __SELECT__ data is used is given below:

Question: How do you __list__ all __users__ records with __age > 55__ in this table?

``` +-------+-------------------------------------------------------------------------------------------------------------------------------+
| Table | Create Table                                                                                                                  |
+-------+-------------------------------------------------------------------------------------------------------------------------------+
| users | __CREATE TABLE__ `users` (
  `id` int(11) __DEFAULT NULL__,
  `name` varchar(256) __DEFAULT NULL__,
  `age` int(11) __DEFAULT NULL__
) __ENGINE__=InnoDB __DEFAULT CHARSET__=latin1 |
+-------+-------------------------------------------------------------------------------------------------------------------------------+


Answer: __SELECT * FROM__ users __WHERE age > 55__;

> All comments, feedbacks and suggestions are highly welcome. Kindly take a look at my
codes in this project to get an insight. Scroll up :arrow_up:, please.

##  Author :black_nib:
*  __Oyindamola Ibis__ <[HBIbidunni](https://github.com/HBIbidunni)>
