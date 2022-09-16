---
layout: project
type: project
image: img/vacay/bank.jpg
title: "Bank Software"
date: 2022
published: true
labels:
  - C
  - Linked Lists
  - Modular Programming
summary: "A simulated bank record database project for ICS 212."
---

This program is a simple bank record database that uses a linked list to store user profiles. This software combines a number of topics such as user I/O, data structures, error handling, modular programming and makefile. The application promts the user with a list of menu options, allowing them to do things like add and delete records from the database. The front-end and back-end are completely independent and modular in this programming, meaning that the database functions that run in the back-end can be easily linked to a more sophisicated, non console based user interface program. The program also contains a number of minor details to increase real wold usability, such as accepting multi line input for addresses and handling accounts with duplicate identifier numbers.

## Here is a sample of the program running.

<hr>

<pre>

Please select a menu option
add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account # as a key
quit: quit the program

add

Enter the account number: 12345

Enter name for acount: Evan Araki

Enter address(end input with a semicolon):
44-404 Street
Unit 90
Manoa, Hawaii;

Record added

Please select a menu option
add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account # as a key
quit: quit the program

printall

**ALL RECORDS**
***************************************************************
12345
Evan Araki
44-404 Street
Unit 90
Manoa, Hawaii
***************************************************************


Please select a menu option
add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account # as a key
quit: quit the program

delete

Enter the account number: 12345

Record deleted

Please select a menu option
add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account # as a key
quit: quit the program

find

Enter the account number: 12345

The record with that account number could not be found

Please select a menu option
add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account # as a key
quit: quit the program

printall

**ALL RECORDS**
<hr>

Source: <a href="https://github.com/EvanAraki/bankapp">EvanAraki/bankapp</a>

