# IRCTC Ticket Booking System (Backend)

This project is a backend simulation of the IRCTC railway ticket booking system, developed using **Java** and **MySQL**. It provides command-line access to core features such as train search, ticket booking, cancellation, and user login/registration.

## 🔧 Features

- 👤 User Registration & Login
- 🚆 Train Search (by Source & Destination)
- 🎟️ Ticket Booking with Seat Availability Check
- ❌ Ticket Cancellation
- 📄 PNR Generation
- 🗂️ Admin Functionality to Add Train Records
- 💾 MySQL Database Integration using JDBC

## 🛠️ Technologies Used

- Java (Core Java, JDBC)
- MySQL
- OOP Principles
- Command-Line Interface (CLI)

## 📂 Project Structure

ticketBooking/
├── src/
│ ├── Main.java
│ ├── DBConnection.java
│ ├── User.java
│ ├── Train.java
│ └── ... (other logic classes)
└── README.md

## 🗃️ Database Setup

### Prerequisites
- MySQL Server Installed
- Java JDK 8 or higher
- Any Java IDE (Eclipse, IntelliJ, etc.)

### Steps

1. **Create the Database**
   - Name it: `irctc`
   - Create tables for `users`, `trains`, `bookings`, etc.
   - (Ask me if you want a sample SQL schema file!)

2. **Update DB Credentials**
   - In `DBConnection.java`, edit the connection string:
     ```java
     String url = "jdbc:mysql://localhost:3306/irctc";
     String username = "root";
     String password = "<your-password>";
     ```

3. **Run the Application**
   - Execute `Main.java` to access the CLI booking system.

## 🚀 Future Enhancements

- Add a **JavaFX or Web Frontend**
- Implement **hashed passwords** for security
- Add **booking confirmation via email**
- Include **admin authentication**

## 👤 Author

**Sibasish**  
Computer Science Student | Backend Developer  
🔗 [GitHub](https://github.com/Sibasish41)

---

*Feel free to clone or fork this project. Contributions are welcome!*

