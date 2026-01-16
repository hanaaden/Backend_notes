# DDL(data definition language)
Manages the structure of the database frameworks 
While data manipulation language DML handles the actual data (rows and records) 
## Most common DDL commands are
**CREATE** to create new objects in your database 
**ALTER** to modify an existing objects 
**DROP**to remove a entire object including its data
**TRUNCATE** to delete all rows in the table but stricken of the table remains

# GENERATED ALWAYS AS IDENTITY (Primary Key) vs serial


Both is being used to auto increment 
But ALWAYS AS IDENTITY (Primary Key) IS A modern standard 

When you need to auto increment columns sometimes when you need you can manually enter the SERIAL key into your database but ALWAYS AS IDENTITY (Primary Key)
Will not allow you that

# Why GENERATED ALWAYS AS IDENTITY is better 

Cuz its modern standard SQL 
SERIAl is only Postgres syntax 
While GENERATED ALWAYS AS IDENTITY is official SQL standard
Works across databases (Postgres, SQL Server, Oracle, etc.)

# GENERATED ALWAYS AS IDENTITY  vs uuid 

GENERATED ALWAYS AS IDENTITY  is easy to read 
While uuid is hard to read 
And slow 
Uuid is hard to guess 

GENERATED ALWAYS AS IDENTITY uses auto increment numbers 
Which makes it faster 
while a UUID is a long, randomly generated identifier that is harder to read and slightly slower but is globally unique