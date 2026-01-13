Hospital Management System

A console-based Hospital Management System developed using Java, JDBC, and MySQL. This project allows basic management of hospital operations such as handling doctors and patients through database connectivity.


---

🚀 Features

Add and view doctors

Add and view patients

Fetch doctor details by ID

MySQL database integration using JDBC

Clean and simple console-based interface



---

🛠️ Technologies Used

Java (Core Java)

JDBC (Java Database Connectivity)

MySQL (Relational Database)

IntelliJ IDEA (IDE)

Git & GitHub (Version Control)



---

📂 Project Structure

HospitalManagementSystem/
│
├── src/
│   ├── Doctor.java
│   ├── Patient.java
│   ├── HospitalManagementSystem.java
│   └── Main.java
│
├── .gitignore
└── README.md


---

⚙️ Database Setup

1. Create a database in MySQL:

CREATE DATABASE hospital;


2. Create required tables (example):

CREATE TABLE doctors (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    specialization VARCHAR(100)
);
