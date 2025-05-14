# SQLConstraints
SQL constraints are rules applied to the data in a table to ensure its accuracy and reliability. Constraints are of two levels:Column level,Table level.

1.PRIMARY KEY:
A primary key is a column or set of columns that uniquely identifies a row in a table. It’s created on a 
table and ensures that the values in that column or columns must be unique and not NULL. 
This is often done using some kind of numeric ID field but doesn’t have to be.

2.FOREIGN KEY:
A foreign key is a field in a table that refers to a primary key in another table. It is used to link the 
record in the first table to the record in the second table.

3.UNIQUE KEY:
A unique constraint is a constraint on a table that says that a column or set of columns needs to have 
unique values. 
It’s different to a primary key in that a table can only have one primary key, but a table can have zero, 
one, or many unique constraints. 
Unique constraints can also allow NULL values, but primary keys cannot.

4.NOT NULL:
Ensures that a column cannot have a NULL value. This constraint is used to enforce that a column must always contain a value.

5.CHECK:
Ensures that the values in a column satisfy a specific condition.

6.DEFAULT:
 Sets a default value for a column if no value is specified.
