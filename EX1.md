# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE: 4/8/23
## AIM:
To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY:
```
SQL> CREATE TABLE student_table(rollno int, name varchar(20), age int,
address varchar(20), phoneno int);
```

### OUTPUT:
![image](https://github.com/AJAYASWIN-M/G2_DBMS/assets/118679692/78495314-c42b-4885-bb3e-bb5220678d3e)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
SQL> ALTER TABLE student_table ADD department varchar(10);
```
### OUTPUT:
![image](https://github.com/AJAYASWIN-M/G2_DBMS/assets/118679692/c760abdb-97f9-4ae9-82e7-670c7a46c159)

### 3) Drop the student table
 
### SQL QUERY: 
```
SQL> DROP TABLE student_table;
```

### OUTPUT:
![image](https://github.com/AJAYASWIN-M/G2_DBMS/assets/118679692/60a5aff1-0a4d-40dd-9039-d6250f972f3e)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
SQL> TRUNCATE TABLE student_table;
```


### OUTPUT:
![image](https://github.com/AJAYASWIN-M/G2_DBMS/assets/118679692/a2504cc7-76cb-4683-b6ae-e76e00cba457)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```
SQL> ALTER TABLE student_table RENAME TO my_student;
```
### OUTPUT:
**![image](https://github.com/AJAYASWIN-M/G2_DBMS/assets/118679692/e5991cc7-e809-4884-819c-ee03d3321f66)
**
## Result:
Thus the table student database is created and DDL queries are executed successfully.
