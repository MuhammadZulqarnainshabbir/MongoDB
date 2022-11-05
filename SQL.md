Differnt Subset of SQL

DDL : Data Defination Language 
DML : Data Manipulation Language
DCL : Data Controll Language
TCL : Data Manipulation Language


### DDL Include (CREATE, DROP, ALTER, TRUNCATE) Statement
    - Create is used in DDL to create database object like table views and Function
    - Drop is used in DDL to drop or delete database objects like tables, views and function
    - Alter is used in DDL to modify the structure of database objects.
    - TRUNCATE is used to delete all the data from a table at once
### DML Include (INSERT UPDATE DELETE, MERGE) Statement
    - Insert  will add a row or reccord to the table
    - Update will modify the data in the table
    - Delete will remove one or multiple statement in the table
    - Merge statement will either do an update or insert based on the available.
    
### DCL Include (GRANT AND REVOKE)
     - GRANT statement use to provide access privileges to a database object to any database or schema
     - REVOKE statement are used remove access privileges from a database object from any database or schema
### TCL Include ( COMMIT, ROLLBACK, SAVEPOINT) Statement

     - Commit statement will permanently save any open transaction, by transactions i mean any changes done to any database table.
     - RollBack statement will remove any open transactions, i mean changes done using DML statements like insert, update, Delete, Merge.
     - Savepoint statement can be used to create a specifc pointer in your session and provide a name to this you can to ths pointer. you can either rollback or commit transaction only until this point.

# Case Statement
 - case Statement is similar if else statement in other progrmming languages we can use it fetch or show a particular value based on certain condition.
 
  
### DQL includes (SELECT) Statement
     - Select Statement is used to fetch and view data from the database,


# differnce between DELETE and Truncate
     - Delete statement can be use to remove either few or all the records table, whereas truncate will always remove all the records from table. Truncate cannot have where condition
     - Delete is DML statement thats why we need to commit changes in order to save them while , truncate is DDL statement so we any commit is not required
