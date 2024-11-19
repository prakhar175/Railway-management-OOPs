# Railway Management System

A comprehensive **Railway Management System** built using C++ and Object-Oriented Programming (OOP) principles. This program allows users to book train tickets, manage passenger details, view ticket details, and access an integrated E-Catering service.

---

## 📜 Features

- **Passenger Management:**
  - Add customer details for up to 6 passengers.
  - Automatically generate and assign a unique PNR number.

- **Train Booking:**
  - Choose from multiple destinations (e.g., Delhi, Kolkata, Jaipur).
  - Select class (3A, 2A, 1A) and view ticket charges.

- **Ticketing System:**
  - Generate a ticket, calculate total charges, and save data to CSV files.
  - Display tickets and saved database records.

- **E-Catering Service:**
  - View food menu, order meals, and print receipts.
  - Maintain a record of food orders for each PNR.

- **Database Management:**
  - Store passenger details and booking records in `records.csv`.
  - Access and delete data from the database.

- **OOP Principles:**
  - Classes and Inheritance (e.g., `Details`, `Registration`, `Ticket`, `OrderFood`).
  - Encapsulation for data protection and modularity.

---

## 🛠 Requirements

To run this project, you need:
- A C++ compiler (e.g., GCC, Clang, or MSVC).
- Standard Template Library (STL) support.
- A terminal or IDE (e.g., Code::Blocks, Visual Studio, VS Code).

---
## 🧩 Classes and Architecture

1. **Management**: Initializes the program and displays the main menu.
2. **Details**: Handles passenger details and PNR generation.
3. **Registration**: Allows train booking and fare calculation.
4. **Ticket**: Generates tickets and interacts with the database.
5. **OrderFood**: Implements the E-Catering service.

---

## 📝 Notes

- Maximum booking limit is **6 passengers per ticket** same as IRCTC.
- All database operations use plain text CSV files.

---


