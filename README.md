# Guided Project-Answering Business Questions using SQL

In this guided project, we're going to practice using our SQL skills to answer business questions.

We'll use Chinook database which provided as a SQLite database file called `chinook.db`. 
A copy of the database schema is below - we need to come back and check the connection between each other very often.

![scema diagram](https://s3.amazonaws.com/dq-content/191/chinook-schema.svg)

It's worth remembering that our database retains 'state', so if we run a query with a CREATE or DROP twice, the query will fail. 
If you have trouble, or if you manage to lock your database, we have provided a chinook-unmodified.db file that you can copy 
over the chinook.db to restore it back to its initial state

Here are a few tips to keep in mind while working on these queries:

- Write your query in stages, and run it as you go to make sure at each stage it's producing the output you expect.
- If something isn't behaving as you expect, break parts of the query out into their own, separate queries to make sure there's not an inner logic error.
- Don't be afraid to write separate queries to check the underlying data, for instance you might write a query that you can use to manually check a calculation and give yourself confidence that the output you're seeing is correct.
- If you do get stuck, don't forget your [support options](https://www.dataquest.io/help/article/yJqIwwQFW9-what-support-do-i-get).
