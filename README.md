
# Banking System Project

A Java-based banking system application that provides secure banking operations with a graphical user interface.

## Features

- Customer Account Management
- Account Balance Inquiries 
- Deposit & Withdrawal Operations
- Transaction History
- Secure Login System
- MySQL Database Integration

## Prerequisites

- Java JDK 8 or higher
- MySQL Server
- MySQL Connector/J JDBC Driver
- Database named 'bank' running on localhost:3306

## Database Configuration

The application connects to MySQL with these default settings:
- URL: jdbc:mysql://localhost:3306/bank
- Username: root
- Password: root

## Running the Application

There are two ways to run the application:

1. Using the JAR file:
```bash
java -jar BankingSystemProject.jar

2. Running from source code:
javac src/com/obs/mainwork/MainGUI_Desktop.java
java src.com.obs.mainwork.MainGUI_Desktop

Project Structure
src/com/obs/bean/ - Data models
src/com/obs/dao/ - Database operations
src/com/obs/utility/ - Utility classes
src/com/obs/mainwork/ - Main application files

Security Features
Password-protected accounts
Secure database transactions
Input validation
Exception handling#   O n l i n e - b a n k i n g - s y s t e m  
 