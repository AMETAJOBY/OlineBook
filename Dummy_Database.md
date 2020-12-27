### Copy and Paste the following MYSQL commands to make a dummy database for this Project :


create database onlinebookshop;

use onlinebookshop;

create table books(barcode varchar(100) primary key, name varchar(100), author varchar(100), price int, quantity int);

create table users(username varchar(100) primary key,password varchar(100), firstname varchar(100),lastname varchar(100),address text, phone varchar(100),mailid varchar(100),usertype int);

insert into books values('10101','Programming in C','James k Jose',500,5);

insert into books values('10102','Learn Java','Scott Malcum',150,13);

insert into books values('10103','Database Knowledge','Charles Petre',124,360);

insert into books values('10104','Let us c++','Steve Mac',90,111);

insert into books values('10105','Success Key','Ameta Joby',5000,15);

insert into users values('User','Password','First','User','My Home','42502216225','User@gmail.com',2);

insert into users values('Admin','Admin','Mr.','Admin','Haldia WB','9584552224521','admin@gmail.com',1);

insert into users values('Ameta','Ameta','Ameta','Joby','Ekm','1236547089','ametamercy@gmail.com',2);

commit;
