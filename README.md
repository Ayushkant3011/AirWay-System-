# AirWay-System++



# Project Overview
Airway System++ is an airline reservation system developed using C++ and MySQL, utilizing Object-Oriented Programming (OOP) concepts. This project is designed to allow users to book, manage, and view airline reservations.
The system integrates a MySQL database to store and retrieve flight, user, and booking data in real time.

# Features
Real-Time Availability:
Provides dynamic seat selection and real-time updates on available seats for flights.
Ensures that users can view accurate seat availability when making reservations.

Transaction Management:
Securely handles booking confirmations.
Stores ticket and transaction details in the MySQL database for future reference and audit.
Modular and Scalable Design:

Developed using OOPs principles like classes to ensure modularity and scalability.
Allows easy addition of new features and updates without affecting the existing system.

# Technologies Used
Programming Language: C++
Database: MySQL
Database Integration: MySQL Connector for C++
OOP Concepts

# System Architecture
Backend:
The core functionality of the project is handled using C++ where different OOP components manage flight schedules, reservations, user data, and transaction processes.

Database Integration:
A MySQL database is integrated using the MySQL Connector for C++ to store, retrieve, and manage data dynamically. It handles flight records, booking details, and user information.

Real-Time Updates:
The system ensures real-time seat availability for flights through direct interaction with the database, dynamically updating seat status as users book or cancel reservations.
Installation & Setup
Clone the repository to your local machine.

Copy code
git clone https://github.com/yourusername/airway-system-plus-plus.git

Set up MySQL and create the necessary database and tables. You can find the SQL script to set up the tables in the /sql folder.

Install MySQL Connector for C++ to enable the integration between C++ and MySQL.

Compile and run the project using your preferred C++ compiler.

How to Use
Start the program by executing the main C++ file.
Follow the prompts to book, cancel, or modify reservations.
The system will interact with the database to display real-time seat availability and store all booking details.
