CREATE DATABASE {db_name}  
USE {db_name} // just like import command in python

CREATE TABLE table _ name (                      CREATE TABLE student (
column_namel datatype constraint,                id INT PRIMARY KEY,
column_name2 datatype constraint,                name VARCHAR(50),
column_name2 datatype constraint                 age INT NOT NULL
);                                               );


INSERT INTO student VALUES(1 , "Abhi" , 22);
INSERT INTO student VALUES(2 , "ABC" , 21);



