# Homework-3-SQL-solution

Download Here: [Homework #3: SQL solution](https://jarviscodinghub.com/assignment/homework-3-sql-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Objectives
➢ Become familiar with SQL language & syntax for SELECT queries, DDL and DML
➢ Become familiar with a tool of your choice for building and submitting queries (whether command mode or GUI.)
➢ Successfully run the scripts necessary to create a sample database consisting of 8 tables, verify that your database is correctly built.
➢ Use SQL your database to answer the assigned problems.
Pre-Processing
Step1: Download and Install PostgreSQL/PostgresAdmin
Please follow the installation guide, if you haven’t installed it https://moodle.cs.colorado.edu/pluginfile.php/112893/mod_resource/content/1/Class_%20PostgreSQL%20Installation.pdf
In this homework, if you want to use console or the Admin too, You are free to use either one. The guide is for your VM or Ubuntu system. If you have any other operating system, please download the respective installer for it.
Step2: Creating the tables
Download a Script folder from Moodle under HW3. There are 8 scripts files to create 8 tables and insert values inside these tables. Before creating these tables, you have to create on database. Please read the below instruction carefully.
Before you can create your database, you need to make sure that your instance of PostgreSQL is running.
To check your instance is running or not, Open a new terminal and type “service postgresql status”, if the status is Active then your postgreSQL is running. If the status is inactive or dead, then type “service postgresql start” and hit enter and type your system password when the window is pop-up.
Follow this writeup to start your postgreSQL: https://moodle.cs.colorado.edu/pluginfile.php/112893/mod_resource/content/1/Class_%20PostgreSQL%20Installation.pdf
Do the following:
1. Create a Database: create database company WITH ENCODING ‘LATIN9’ LC_COLLATE = ‘C’ LC_CTYPE=’C’ TEMPLATE=template0;
2. Open a new terminal and go to the directory where you download your script files from Moodle. Go inside this directory and use ls command and it will list out all the files. You will get below files in the folder.
a. categories.sql
b. employees.sql
c. orders.sql
d. order_details.sql
e. customers.sql
f. products.sql
g. suppliers.sql
h. shipper.sql
3. Import all the tables from your SQL files inside your database named “company”.
a. To import, please type in your terminal sudo su postgres and it will ask your system password and then type
psql company



