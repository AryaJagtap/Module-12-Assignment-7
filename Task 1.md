# Module 12 : Building Database Apps with PostgreSQL & Python

## 12.1 : Introduction to data
No Code

## 12.2 : Introduction to database
No Code

## 12.3 : Introduction to PostgreSQL
No Code

## 12.4 : Installing PostgreSQL
No Code

## 12.5 : Creating a database
  - \l                               : list all databases
  - create database demodb;          : create database
  - \c demodb                        : connect database

Here i have created database names "demodatabase".    

<img width="1920" height="1080" alt="Screenshot (486)" src="https://github.com/user-attachments/assets/e2583bb3-263f-4063-a767-eb1fca0f46bb" />

## 12.6 : Deleting a database
  - drop database demodatabase;      : delete the database

Here i have deleted "demodatabase".   

<img width="1920" height="1080" alt="Screenshot (487)" src="https://github.com/user-attachments/assets/81dcde4a-a6c1-4b04-a4be-4e45275f3e70" />

## 12.7 : Creating table and adding data
  - CREATE TABLE mango (colour text, dozen int, price int);                  : to create table
  - \d                                                                       : to check the relations
  - INSERT INTO mango (colour, dozen, price) VALUES ('yellow', 5, 2500)      : to insert data

Here i have created a database names "fruits" and created table named "mango" inside this database, which further has attributes "colour, dozen, price".
Also i have inserted 2 sets of data in this table.    

<img width="1920" height="1080" alt="Screenshot (488)" src="https://github.com/user-attachments/assets/9e813292-b1ad-4d80-8c25-7e7427132c35" />


## 12.8 : Retrieving data from database and deleting contents in the table
  - SELECT * FROM mango;                              : to retrive(see) whole data [* means all]
  - SELECT colour FROM mango;                         : to retrive(see) only specific coloum of the table
  - SELECT * FROM mango WHERE price = 2500;           : to retrive(see) data using conditions. [after WHERE specific condition is used "price = 2500"]
  - TRUNCATE TABLE mango;                             : to delete all the data from the table.

Here i have retrived the data. Data has been retrived all in once and also using specific conditions like name and price.    
Also at the end table is cleared.

<img width="1920" height="1080" alt="Screenshot (489)" src="https://github.com/user-attachments/assets/6302fa48-1a3e-4c3c-b4af-f722d40fe71d" />


## 12.9 : Setting up virtualenv
  - pip install virtualenv      : to install virtual env
  - virtualenv env              : to create virtual env [virtualenv (env name)]
  - cd env                      : to enter virtual environment folder
  - cd Scripts                  : to enter Scripts folder
  - activate                    : to activate virtual environment
  - deactivate                  : to deactivate virtual environment
  - cd ..                       : to go into previous directory
  - python test.py              : to execute(run) python file [python (file name)]
  - 
## 12.10 : Installing psycopg2
## 12.11 : Connecting to the database
## 12.12 : Creating table using python
## 12.13 : Inserting the data using python
## 12.14 : Extracting the data from the database
## 12.15 : Adding the input from the user
