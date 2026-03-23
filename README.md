
# 🚌 Bus Reservation System (Java + JDBC)

## 📌 Overview

The **Bus Reservation System** is a console-based Java application that allows users to:

* View available buses
* Book tickets
* Check seat availability based on date

It uses **JDBC** to interact with a MySQL database for storing and retrieving booking and bus details.

---

## 🚀 Features

* Display all available buses
* Book tickets with passenger details
* Check seat availability before booking
* Store bookings in database
* Date-based reservation system

---

## 🛠️ Tech Stack

* **Java** (Core Java, OOP)
* **JDBC**
* **MySQL**
* **SQL**

---

## 📂 Project Structure

```
com.BusReservation
│
├── Booking.java        # Handles booking input and availability check
├── BookingDAO.java     # Database operations for bookings
├── Bus.java            # Bus model class
├── BusDAO.java         # Database operations for bus data
├── BusDemo.java        # Main class (entry point)
├── DbConnection.java   # Database connection setup
```

---

## ⚙️ Configuration

Update database credentials in:

**DbConnection.java**

```java
private static final String url = "jdbc:mysql://localhost:3306/busreservation";
private static final String userName = "root";
private static final String passWord = "your_password";
```

---

## ▶️ How to Run

1. Clone the repository
2. Open in any Java IDE (Eclipse / IntelliJ)
3. Add MySQL JDBC Driver (Connector/J)
4. Run:

```
BusDemo.java
```

---

## 🧪 Sample Flow

```
Bus No: 1
AC: yes
Capacity: 40
------------------------------------------

Enter 1 to Book and 2 to exit : 1
Enter name of passenger: Arun
Enter bus no: 1
Enter date dd-mm-yyyy: 25-03-2026

Your booking is confirmed
```

## 👨‍💻 Author

**Arun Vignesh V**

---
