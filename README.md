# 🚦 Transport Management System – Java OOP Project

A smart and scalable **Transport Management System** developed using **Java Object-Oriented Programming** principles. Built in **IntelliJ IDEA** with **MySQL database integration via JDBC**, this project handles vehicle registration, route assignment, and passenger bookings with clean, modular code.

---

## 📌 Project Highlights

✅ **Language:** Java  
✅ **IDE:** IntelliJ IDEA  
✅ **Database:** MySQL  
✅ **Database Connectivity:** `mysql-connector-java` (JDBC)  
✅ **Concepts Used:** Encapsulation, Inheritance, Abstraction, Polymorphism  

---

## 💡 Features Overview

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🚌 Vehicle Management          | Add, update, or delete vehicle information                                 |
| 📍 Route Allocation            | Assign and manage travel routes for each vehicle                           |
| 👤 Passenger Booking           | Record and manage passenger bookings and info                              |
| 🔄 Database Integration        | Real-time read/write with MySQL database using JDBC                        |
| 🧠 OOP Principles Applied      | Clean, modular structure for maintainability and reuse                     |

---

## 📁 Project Structure
TransportManagementSystem/
│
├── src/
│ ├── models/ # Classes for Vehicle, Passenger, Route (POJOs)
│ ├── database/ # DB connection and query classes
│ └── main/ # Main logic, menus, system execution
│
├── lib/ # mysql-connector-java.jar
├── transport.sql # SQL file to create DB schema
└── README.md


---

## 🛠️ How to Run the Project

Follow these steps to set up and run the project in IntelliJ IDEA:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/transport-management-system.git
Open in IntelliJ IDEA

File > Open > Select the project folder

Add JDBC Library

Download mysql-connector-java

Go to: File > Project Structure > Libraries > Add JAR

Choose the mysql-connector-java.jar file

Create MySQL Database

Open transport.sql in MySQL Workbench or any SQL tool

Run the script to create tables

Update Database Config

In the DB connection file, update:

java
Copy
Edit
String url = "jdbc:mysql://localhost:3306/your_database";
String username = "your_username";
String password = "your_password";
Run the Application

Right-click on the main class → Run

🧠 Core OOP Concepts Used
Concept	Example in Code
Encapsulation	All class fields are private with public getters/setters
Inheritance	Common properties shared through a base class
Polymorphism	Method overriding for flexible behavior
Abstraction	Interface for database operations

🎯 Learning Outcomes
✅ Practical experience in real-world Java OOP application

✅ Hands-on with MySQL database and JDBC connectivity

✅ Writing maintainable, clean, and scalable code

✅ Understanding system flow and class interaction

⚠️ Disclaimer
This project is developed for educational purposes as part of a university assignment. It is not production-ready but demonstrates strong foundational concepts in Java and backend development.

🙌 Acknowledgements
Built with 💻, ☕, and late-night debugging by Inshal and my TEam members(M.Anas, M.Ismail shah, M.Moeen & M.Rehan Malik Siddique)
If you like this project, feel free to ⭐ it!
