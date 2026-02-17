# Airplane Ticket Reservation System (ATRS)

A comprehensive Java-based desktop application designed to streamline the flight booking process for passengers and administrators. This project was developed using **Java Swing** for the GUI and **MySQL** for backend data management.

## 🚀 Features
* **User Authentication:** Secure Sign Up and Login modules for passengers.
* **Flight Search:** Search for Domestic and International flights based on origin, destination, and date.
* **Flight Selection:** View real-time flight details, including Flight ID, Airline name, and Departure time.
* **Payment Gateway:** Simulated payment process supporting both Credit and Debit card validation.
* **Ticket Generation:** Automatic generation of a digital boarding pass after successful payment.
* **Admin Control:** Capability to manage flight schedules and seat availability.

## 🛠 Technology Stack
* **Language:** Java 8
* **IDE:** NetBeans
* **Database:** MySQL
* **Connector:** JDBC (Java Database Connectivity)
* **GUI Library:** Java Swing / AbsoluteLayout

## 💻 Hardware Requirements
* **RAM:** 12GB (Recommended)
* **Storage:** 200GB HDD/SSD
* **Standard Peripherals:** Keyboard, Mouse, Monitor

## ⚙️ Setup Instructions
1. **Database Setup:**
   * Import the provided `database.sql` file into your MySQL server.
   * Ensure the database name is `java_project`.
   * Update the database credentials (URL, Username, Password) in the source code (found in `home.java`, `login.java`, etc.).

2. **Project Import:**
   * Open NetBeans IDE.
   * Go to `File > Open Project` and select this repository folder.
   * Add the `mysql-connector-java.jar` to the project libraries.

3. **Execution:**
   * Run `home.java` to start the application.

## 👥 Contributors
* Aadarsh Pranav Suresh Babu (22MIS0126)
* K.C Ghorav (22MIS0243)
* K. Venkateswara Reddy (22MIS0104)

## 🎓 Acknowledgments
Submitted as a project report for **Programming in Java (SWE1007)** under the guidance of **Prof. Anitha.A**.
