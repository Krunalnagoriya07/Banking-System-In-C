Here is a Banking System project I developed in C.

This project is focused on customer account services in bank.

Here, one could create a new account, update information of an existing account, view and manage transactions, check the details of an existing account, remove existing account and view customers’ list.

Overall, with this project, you can perform banking activities like in a REAL bank. This project is a console application without graphics, and compiled in Code::Blocks with gcc compiler.

Project is password protected (password is codewithc). 

Functions used in Banking System

The source code for Customer Account Bank Management System considerably easy to understand. I have divided this into many functions, most of which are related to different banking activities, listed below are some of the more important functions which may help you understand the project better.

menu() – This function displays the menu or welcome screen to perform different banking activities mentioned below.

new_acc() – This function creates a new customer account. It asks for account holder’s personal and banking details; such as name, date of birth, citizenship number, address and Phone Number. You can enter the amount to deposit and choose one type of deposit account – saving, current, fixed for 1 year, fixed for 2 years or fixed for 3 years.

view list() – With this function, you can view the customer’s banking information such as account number, name, address and phone number provided while creating the account.

edit() – This function has been used for changing the address and phone number of a particular customer account.

transact() – With this function, you can deposit and withdraw money to and from a particular customer account.

erase() – This function is for deleting a customer account.

see() – This function shows account number, name, date of birth, citizenship number, age, address, phone number, type of account, amount deposited and date of deposit. It also displays the amount of interest corresponding to a particular account type.

In this banking system project in C, file handling has been used for almost all functions. File has been used to store data related to new account, transaction, editing of account information and viewing of account information. I haven’t used file handling for the menu, interest calculation and password.
