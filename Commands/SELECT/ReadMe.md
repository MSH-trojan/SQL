The "SELECT" statement is used to select data from a database (Note: SQL in most of the databse 
systems is not case sensitive so here, the "SELECT" is no different than "select")

here is an example of returning data from the customers table:

1  SELECT CustomerName, City FROM Customers;

the general syntax is as follows:

1  SELECT column1, column2, ...
2  FROM table_name;

However, if we intend to return all columns, without specifying every column name, we can use the 
syntax below:

1  SELECT * FROM Customers;


here the "SELECT *" resembles all the columns to be returned.
