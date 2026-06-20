# 📇 Contact Management System

A comprehensive console-based Contact Management System developed in **Java** that allows users to securely manage their personal contacts through **account-based authentication, file handling, contact management operations, and persistent data storage**.

The system provides individual user accounts, ensuring that every user's contact list remains private and accessible only after successful authentication.

---

# ✨ Features

## 👤 User Account Management

* Create a new user account
* Secure login using User ID and Password
* Unique User ID validation
* Persistent account storage using file handling
* Personalized user contact management

## 📞 Contact Management

* Add new contacts
* View all saved contacts
* Search contacts by phone number
* Search contacts by name
* Partial name search support
* Update existing contact details
* Delete contacts
* Duplicate contact prevention

---

# 💾 File Handling

The project uses text files for persistent data storage and user-specific contact management.

### Files Used

| File Name               | Purpose                                         |
| ----------------------- | ----------------------------------------------- |
| `userLogin.txt`         | Stores user credentials and account information |
| `contacts_<UserID>.txt` | Stores contacts belonging to a specific user    |

### Sample Storage Format

#### User Information

```text
101|password123|Rahul Gupta
102|admin123|Aman Verma
```

#### Contact Information

```text
9876543210|Aman Verma
9123456789|Priya Sharma
9988776655|Rohit Singh
```

---

# 🔐 Authentication & Security Features

The system incorporates basic security mechanisms to protect user data:

* User ID based authentication
* Password verification
* Unique account creation validation
* Contact ownership isolation
* Duplicate contact detection
* Input validation for phone numbers
* Protected access to personal contact lists

---

# 📋 Contact Operations

### Contact Management Features

* Create Contact
* View Contact List
* Search Contact by Number
* Search Contact by Name
* Update Contact Details
* Delete Contact

### Search Features

* Exact number search
* Name-based search
* Partial name matching
* Multiple matching records display

---

# ⚠️ Validation & Error Handling

The project includes extensive validation and exception handling:

* Invalid User ID detection
* Duplicate User ID prevention
* Invalid login credential handling
* Invalid phone number detection
* Duplicate contact prevention
* Empty contact list handling
* Missing file handling
* Corrupted record validation
* File access exception handling

---

# 🧠 Concepts Used

* Object-Oriented Programming (OOP)
* File Handling
* Exception Handling
* Java Collections Framework (`ArrayList`)
* Authentication Systems
* CRUD Operations
* Input Validation
* Search Algorithms
* Data Persistence
* Menu-Driven Programming

---

# 🛠️ Technologies Used

* Java
* Java Collections Framework
* Java File Handling APIs
* BufferedReader & BufferedWriter
* Scanner Class

---

# 🚀 How to Run

## Compile the Program

```bash
javac CONTACT_MANAGEMENT_SYSTEM.java
```

## Run the Program

```bash
java CONTACT_MANAGEMENT_SYSTEM
```

---

# 📁 Required Files

The application automatically creates the required files when needed.

Primary files used:

* `userLogin.txt`
* `contacts_<UserID>.txt`

Example:

```text
contacts_101.txt
contacts_102.txt
contacts_103.txt
```

---

# 📖 Sample Workflow

### Create Account

```text
User ID : 101
Password : password123
Name : Rahul Gupta
```

### Login

```text
User ID : 101
Password : password123
```

### Add Contact

```text
Contact Number : 9876543210
Contact Name : Aman Verma
```

### Search Contact

```text
Search by Number
Search by Name
```

### Update Contact

```text
Old Number : 9876543210
New Number : 9988776655
New Name : Aman Kumar
```

### Delete Contact

```text
Contact Number : 9988776655
```

---

# 🎯 Learning Outcomes

This project helped in understanding practical implementations of:

* Contact Management Systems
* File-Based Database Simulation
* User Authentication Mechanisms
* CRUD Operations
* Search Functionality Design
* Input Validation Techniques
* Data Persistence Strategies
* Exception Handling
* Real-World Console Application Development

---

# 👨‍💻 Developed By

## Rahul Gupta

---

# 📖 Project Overview

This project was developed as a practical implementation of a Contact Management System using Java. The objective was to simulate how modern contact management applications organize, store, search, update, and maintain user information while providing secure access through user authentication.

The project demonstrates the practical application of Java fundamentals such as file handling, authentication systems, CRUD operations, collections, exception handling, and persistent data storage without relying on external databases. It serves as an excellent learning exercise in building real-world console-based software systems.
