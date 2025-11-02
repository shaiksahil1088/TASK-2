# 🧠 Basic CRUD Application – ApexPlanet Internship (TASK-2)

## 📘 Project Overview

This project is a **Basic CRUD (Create, Read, Update, Delete)** web application built using **PHP** and **MySQL** as part of the **ApexPlanet Internship (Task-2)**.  
It demonstrates how to build a simple, functional web app that allows users to manage student records securely.

---

## 🎯 Objectives
- Develop a simple web application to perform **CRUD operations**.  
- Implement **basic user authentication** (login and registration).  
- Apply **secure coding practices** using prepared statements and validation.

---

## 🧩 Features
✅ Add new students  
✅ View student list  
✅ Edit student details  
✅ Delete a single student securely (prepared statements)  
✅ Database connection with `config.php`  
✅ Simple and clean UI using HTML, CSS (and optional Bootstrap)

---

## 🖼️ Screenshots

### ➕ Add New Student
![Add Student](./Screenshot%202025-11-02%20110512.png)

### 📋 Student Records
![Student Records](./Screenshot%202025-11-02%20110542.png)

---

## ⚙️ Setup Instructions

### 1. 🖥️ Install XAMPP
- Download and install **[XAMPP](https://www.apachefriends.org/download.html)**.  
- Start **Apache** and **MySQL** services.

### 2. 🗄️ Database Setup
Open [phpMyAdmin](http://localhost/phpmyadmin) and run:

```sql
CREATE DATABASE student_db;

USE student_db;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL,
    phone VARCHAR(20),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

# 3. 📂 File Structure
TASK-2/
│
├── config.php          # Database connection
├── index.php           # Student list (Read)
├── create.php          # Add student (Create)
├── edit.php            # Update student (Update)
├── delete.php          # Delete student (Delete)
├── style.css           # (Optional) Styling
└── README.md           # Documentation

# 🧠 Learning Outcomes

Understanding CRUD operations in PHP

Using MySQL with mysqli and prepared statements

Applying secure coding practices

Designing a user-friendly form interface

Managing sessions for authentication

# 🧾 Deliverables

✅ A fully functional CRUD application

✅ User authentication module

✅ Database schema documentation

✅ Complete PHP source code

### 👨‍💻 Author

Shaik Sahil
Web Development Intern – ApexPlanet Software Pvt Ltd
