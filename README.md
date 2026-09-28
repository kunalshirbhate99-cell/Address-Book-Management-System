# Address Book Management System

A menu-driven Address Book Management System developed in C for managing contact information efficiently using structures, functions, pointers, and file handling.

## 📌 Project Overview

The Address Book Management System is a command-line application developed in C that allows users to create, search, update, delete, and display contact information.

The project focuses on implementing core C programming concepts such as structures, arrays, pointers, functions, string handling, file handling, validation, and modular programming.

## ✨ Features

- Create new contacts
- List all contacts
- Search contacts
- Edit existing contacts
- Delete contacts
- Validate contact details
- Check duplicate phone numbers
- Check duplicate email addresses
- Save contact information to files
- Load contact information from files
- Menu-driven command-line interface

## 🛠️ Technologies & Concepts Used

- C Programming
- Structures
- Arrays
- Pointers
- Functions
- String Handling
- File Handling
- Input Validation
- Modular Programming
- Command Line Interface

## 📂 Project Structure

```text
AddressBook-NewDesign/
│
├── main.c
├── contact.c
├── contact.h
├── file.c
├── file.h
├── populate.c
├── populate.h
├── addressbook.csv
└── contacts.txt
```

## 📋 Application Menu

```text
+--------------------------------+
|        ADDRESS BOOK MENU       |
+--------------------------------+
|  1. Create Contact             |
|  2. Search Contact             |
|  3. Edit Contact               |
|  4. Delete Contact             |
|  5. List All Contacts          |
|  6. Exit                       |
+--------------------------------+
```

## 👤 Contact Management

The application allows users to manage contact information through a structured data model.

Each contact contains information such as:

- Name
- Phone Number
- Email Address

The Address Book maintains multiple contacts and keeps track of the total number of stored contacts.

## 🔍 Search Functionality

Contacts can be searched using different details such as:

- Name
- Phone Number
- Email Address

This makes it easier to locate a specific contact from the address book.

## ✏️ Edit & Delete

Existing contact information can be modified whenever required.

The application also provides an option to delete unwanted contacts from the address book.

## 💾 File Handling

The project uses file handling to maintain contact information between program executions.

Contact data can be stored and loaded using files, providing persistent storage for the address book.

## ✅ Data Validation

The application performs validation while entering contact information.

Validation includes:

- Name validation
- Phone number validation
- Email validation
- Duplicate phone number checking
- Duplicate email checking

This helps maintain accurate and consistent contact data.

## ⚙️ How to Compile

Compile the source files using GCC:

```bash
gcc main.c contact.c file.c populate.c -o address_book
```

## ▶️ How to Run

Run the compiled program using:

```bash
./address_book
```

## 🧠 Key Learning Outcomes

Through this project, I gained practical experience in:

- Implementing structures in C
- Working with arrays of structures
- Using pointers and functions
- Implementing modular C programs
- Performing file input/output operations
- Handling strings and user input
- Implementing searching, editing, and deletion operations
- Applying input validation
- Debugging and problem solving

## 🎯 Project Type

**C Programming | Data Management | File Handling | CLI Application**

## 👨‍💻 Skills Demonstrated

**C | Structures | Pointers | Arrays | File Handling | String Handling | Modular Programming | Debugging | Problem Solving**
