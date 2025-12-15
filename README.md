# ATM Simulator System

## 📌 Project Overview

ATM Simulator System is a **Java-based console application** that simulates the working of a real ATM. The project is developed using **Core Java, JDBC, and MySQL** and focuses on backend logic, database connectivity, and transaction handling.

This project demonstrates how Java applications interact with relational databases using JDBC and perform secure banking operations.

---

## 🛠️ Tech Stack

* **Java (Core Java, OOP concepts)**
* **JDBC (Java Database Connectivity)**
* **MySQL**
* **Eclipse IDE**

---

## ✨ Key Features

* New account creation
* Secure login using account number and PIN
* Deposit money
* Withdraw money with balance validation
* Balance enquiry
* Mini statement / transaction history
* Data persistence using MySQL database

---

## 🧱 Project Architecture

The project follows **MVC (Model–View–Controller)** architecture:

* **Model**: Handles database logic using JDBC
* **View**: Console-based user interaction
* **Controller**: Controls application flow and user requests

---

## 📂 Project Structure

```
ATM-Simulator-System
│── src/
│   ├── ASimulatorSystem/
│   │   ├── Login.java
│   │   ├── Signup.java
│   │   ├── Signup2.java
│   │   ├── Signup3.java
│   │   ├── Transactions.java
│   │   ├── Deposit.java
│   │   ├── Withdrawl.java
│   │   ├── FastCash.java
│   │   ├── MiniStatement.java
│   │   ├── BalanceEnquiry.java
│   │   └── Conn.java
│── README.md
```

ATM-Simulator-System
│── src/
│   ├── controller/
│   ├── model/
│   └── view/
│── database.sql
│── README.md

```

---

## 🗄️ Database Details
- Database Name: `bankmanagementsystem`
- Database Used: **MySQL**

### Tables Used:
- `login` – stores card number and PIN details
- `signup` – stores personal details of the user
- `signup2` – stores additional account details
- `signup3` – stores account type and services
- `bank` – stores transaction details (deposit/withdrawal)

All database connections are handled using **JDBC** through the `Conn.java` class.

---

## ▶️ How to Run the Project
1. Clone the repository
```

git clone [https://github.com/SrinivasPinisetti/ATM-Simulator-System.git](https://github.com/SrinivasPinisetti/ATM-Simulator-System.git)

```
2. Import the project into **Eclipse IDE**
3. Create a MySQL database and execute `database.sql`
4. Update database username and password in JDBC connection class
5. Run the main class to start the application

---

## 📈 Learning Outcomes
- Practical experience with JDBC
- Understanding of SQL queries and database transactions
- Hands-on experience with backend application development
- Improved debugging and exception handling skills

---

## 👤 Author
**Srinivas Pinisetti**  
GitHub: https://github.com/SrinivasPinisetti

```
