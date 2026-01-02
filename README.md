# 📚 Library Catalog System (OOP)

## 📌 Project Description
The **Library Catalog System** is an Object-Oriented Programming (OOP) project that simulates a real-world library system.
The system allows users to add, search, borrow, and manage books while maintaining records of customers, borrowers, orders, and transactions.

Each entity in the system is modeled as a **class**, applying core OOP concepts such as encapsulation, abstraction, inheritance, and polymorphism.

---

## 🎯 Project Objectives
- Apply **Object-Oriented Programming (OOP)** concepts in a practical project
- Design a modular and scalable system
- Practice class relationships and responsibilities
- Implement file handling and exception handling
- Simulate a real library catalog system

---

## 🧠 OOP Concepts Used
- Classes & Objects  
- Encapsulation  
- Abstraction  
- Inheritance  
- Polymorphism  
- Exception Handling  

---

## 🧩 System Entities (Classes)

### 📘 Book
**Attributes:**
- Book ID  
- Title  
- Author  
- Publication Year  
- Status (Available / Not Available)  
- Price  

---

### 👤 Customer
**Attributes:**
- Customer ID  
- Name  
- Orders  

---

### 🛒 Order
**Attributes:**
- Order ID  
- Book  
- Quantity  
- Price  

---

### 👥 Borrower
**Attributes:**
- Borrower ID  
- Borrower Name  
- Transactions  

---

### 🔁 Transaction
**Attributes:**
- Book  
- Borrower  
- Borrow Date  
- Return Date  

---

### 🏛️ Library
**Attributes:**
- Books  
- Customers  
- Borrowers  

---

## ⚙️ System Functionalities

### 🔐 Admin Functionalities
- Add new books with full details
- Update book information (price, availability, etc.)
- Remove books from the system
- Manage inventory of available books
- Add new borrowers
- Update borrower information
- Remove borrowers from the system

---

### 👤 User Functionalities
- Register and login to the system
- Search for books by title or author
- View book details and availability
- Borrow available books
- View borrowing history and return dates
- System records all borrowing and returning transactions
- Check availability before borrowing
- Calculate fines for late returns
- View list of available books

---

## 📂 File Handling
- File handling is **mandatory**
- Data is read once at the start of the program
- All operations are performed in memory
- Data is saved back to files at the end of the program
- Only **two functions** are used for file reading and writing

---

