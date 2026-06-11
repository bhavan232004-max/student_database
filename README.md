# Student Record Management System

## Overview

The Student Record Management System is a menu-driven application developed in C using a singly linked list data structure. It allows users to manage student records efficiently through various operations such as adding, deleting, modifying, sorting, and displaying records. The project also supports file handling to save and load data, ensuring record persistence across program executions.

## Features

* Add new student records
* Display all student records
* Modify existing records
* Delete a specific record
* Delete all records
* Sort records
* Reverse the linked list
* Save records to a file
* Load records from a file at startup
* Exit safely with data management options

## Technologies Used

* C Programming
* Singly Linked List
* File Handling
* Linux/GCC Compiler

## Project Structure

```
Student_Record_Management/
│
├── main.c
├── header.h
├── add.c
├── delete.c
├── modify.c
├── show.c
├── save.c
├── load.c
├── sort.c
├── reverse.c
└── data.txt
```

## Menu Options

```
A/a : Add New Record
D/d : Delete A Record
S/s : Show the List
M/m : Modify A Record
V/v : Save Records
T/t : Sort the List
R/r : Reverse the List
L/l : Delete All Records
E/e : Exit
```

## Compilation

Use GCC to compile all source files:

```bash
gcc *.c -o student_record
```

## Execution

Run the executable:

```bash
./student_record
```

## Learning Outcomes

* Understanding of Dynamic Memory Allocation
* Implementation of Linked Lists
* File Handling in C
* Modular Programming
* Data Structure Operations

## Future Enhancements

* Search functionality
* User authentication
* GUI implementation
* Database integration
* Advanced sorting and filtering options

## Author

Saravana Bhavan

---

⭐ If you found this project useful, consider giving it a star on GitHub!
