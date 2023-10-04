# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. 
It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
These commands are normally not used by a general user, who should be accessing the database via an application.
## List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).

DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database.

TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. 

RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
### SQL QUERY:
```
create table student (rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![image](https://github.com/SandhiyaR1/G2_DBMS/assets/113497571/af164dd2-746d-48b0-8058-ace54285eb66)

### 2) Change the above student table by adding another attribute department
### SQL QUERY:
```
 alter table student add department char(90);
```
### OUTPUT:
![image](https://github.com/SandhiyaR1/G2_DBMS/assets/113497571/9420ce21-a7fb-4ad7-b4b8-a1f4aa7820fb)

### 3) Drop the student table
### SQL QUERY:
```
 drop table student;
```
### OUTPUT:
![image](https://github.com/SandhiyaR1/G2_DBMS/assets/113497571/3f115969-8a28-4ef6-b00d-462c70f76c6c)

### 4) Delete the student table using truncate keyword
### SQL QUERY:
```
truncate table student;
```
### OUTPUT:
![image](https://github.com/SandhiyaR1/G2_DBMS/assets/113497571/93e08c9a-34ce-4e50-abd2-b05a7e12b91d)

### 5) Rename the student table to mystudent
### SQL QUERY:
```
 alter table student rename to mystudent;
```
### OUTPUT:
![image](https://github.com/SandhiyaR1/G2_DBMS/assets/113497571/2a7e681b-4a8e-4a76-880d-bf18fef0e321)
# Result:
Thus the student database has been created and executed in DDL queries using SQL.
