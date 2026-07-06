<div align="center">

# 🏨 Hotel Reservation System

A console-based Hotel Reservation System built with **Java**, **JDBC**, and **MySQL** to manage hotel bookings through a simple and interactive command-line interface.

![Java](https://img.shields.io/badge/Java-25-orange?style=for-the-badge&logo=java)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)
![JDBC](https://img.shields.io/badge/JDBC-Connectivity-success?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)

</div>

---

## 📖 About

The **Hotel Reservation System** is a Java console application that simplifies hotel reservation management. It enables users to create, view, update, and delete reservations while storing all records in a MySQL database using JDBC.

This project was developed to gain hands-on experience with Java database connectivity, SQL operations, and building real-world CRUD applications.

---

## ✨ Features

- 🛏️ Reserve a room
- 📋 View all reservations
- 🔍 Find room number using Reservation ID and Guest Name
- ✏️ Update reservation details
- ❌ Delete reservations
- 💾 MySQL database integration
- 📊 Clean tabular display of reservation records
- ⏳ Interactive exit animation

---

## 🛠️ Built With

- Java
- JDBC
- MySQL
- IntelliJ IDEA
- Git & GitHub

---

## 📂 Project Structure

```
Hotel-Reservation-System
│
├── src
│   └── HotelReservationSystem.java
│
├── .gitignore
├── README.md
└── Hotel Reservation.iml
```

---

## 🗄️ Database Setup

### Create Database

```sql
CREATE DATABASE hotel_db;
```

### Create Table

```sql
CREATE TABLE reservations (
    reservation_id INT AUTO_INCREMENT PRIMARY KEY,
    guest_name VARCHAR(100) NOT NULL,
    room_number INT NOT NULL,
    contact_number VARCHAR(20) NOT NULL,
    reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## ⚙️ Configuration

Update your database credentials inside the Java source file before running the application.

```java
private static final String url = "jdbc:mysql://localhost:3306/hotel_db";
private static final String username = "root";
private static final String password = "YOUR_PASSWORD";
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/Ayush-Raha/Hotel-Reservation-System.git
```

### Navigate to the project

```bash
cd Hotel-Reservation-System
```

### Open in IntelliJ IDEA

Import the project into IntelliJ IDEA.

### Add MySQL Connector/J

Ensure the MySQL JDBC Driver is added to your project dependencies.

### Run the project

Execute

```
HotelReservationSystem.java
```

---

## 💻 Application Menu

```
===============================
     HOTEL MANAGEMENT SYSTEM
===============================

1. Reserve a Room
2. View Reservations
3. Get Room Number
4. Update Reservation
5. Delete Reservation
0. Exit

Choose an option:
```

---

## 📸 Screenshots

### Home Screen

> Add screenshot here

```
screenshots/menu.png
```

### View Reservations

> Add screenshot here

```
screenshots/view.png
```

### Reservation Successful

> Add screenshot here

```
screenshots/reservation.png
```

---

## 🎯 Learning Outcomes

This project helped me understand:

- Java Database Connectivity (JDBC)
- CRUD Operations
- MySQL Database Management
- SQL Queries
- Exception Handling
- Console Application Development
- Version Control using Git & GitHub

---

## 🚀 Future Enhancements

- User Authentication
- Room Availability Checker
- Search Reservations
- Booking History
- Payment Gateway Integration
- Billing Module
- GUI using JavaFX/Swing
- Spring Boot REST API
- PreparedStatement for improved security
- Maven Project Structure

---

## 🤝 Contributing

Contributions are welcome!

If you have ideas to improve this project:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

### Ayush Raha

GitHub: **https://github.com/Ayush-Raha**

---

<div align="center">

### ⭐ If you found this project useful, don't forget to star the repository!

Made with ❤️ using Java & MySQL

</div>
