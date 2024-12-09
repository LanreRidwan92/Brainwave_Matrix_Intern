# RDBMS For Library Management System

## Introduction
The relational database management system RDBMS is designed for the the Library. It consists of three different tables which are books, loan and member's table.

## Table
As it is being explained earlier, there are three different tables. Below are the info about the three tables.

* Book: This is the table that contains the records of the books in the Library and it has a total number of nine columns which are as (Book_ID, Book_Title, Author, ISBN_Num, Publication_Year, Publisher, Genres, Available_copies and Total_Copies).
* Loan: This is the table comprises of the records of the books loan out already and it has six columns which are (Loan_ID, Book_ID, Membership_ID, Loan_Date, Return_Date and Due_Date).
* Members: This is the table that has the records of the Library members. It also has six columns which are as follows, (Membership_ID, Name, Address, Phone_Number, Email_Address and Membership_Expired).

## Relationships
Loan_ID in the Loan Table is the Primary Key, While Membership_ID and Book_ID from Member and Book's table respectively are the foreign keys.
