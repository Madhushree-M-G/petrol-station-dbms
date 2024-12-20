# Petrol Station Management System

A web-based application designed to streamline and automate the management of petrol station operations. This project helps eliminate manual processes, making data management secure, efficient, and user-friendly.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [System Requirements](#system-requirements)
  - [Software Requirements](#software-requirements)
  - [Hardware Requirements](#hardware-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Database Structure](#database-structure)
- [Conclusion](#conclusion)


---

## Overview
The **Petrol Station Management System** addresses the inefficiencies of manual systems by offering a centralized, digital solution for managing customer data, transactions, and fuel inventory. Built using modern web technologies, it provides a robust platform for petrol station administrators.

---

## Features
- **Search and Track:** Search data based on factors like customers, payments, and fuel type.
- **Data Automation:** Reduces manual work by automating record-keeping and transactions.
- **Efficient Management:** Easy updating and retrieval of data for effective resource utilization.
- **Administrator Access:** Ensures secure access, limited to authorized administrators.
- **Sales Reporting:** Monitor daily sales and generate detailed reports.

---

## System Requirements

### Software Requirements
- Operating System: Windows 10 or higher
- Web Server: XAMPP v3.3.0 (PHP Version 8.0.7)
- Programming Languages: PHP, HTML, CSS, JavaScript, jQuery, Ajax, Bootstrap
- Database: SQLite

### Hardware Requirements
- Processor: Intel Core i5 (7th generation or higher)
- RAM: 4GB or more
- Storage: At least 20GB free space

---

## Installation
1. Clone the repository:
   git clone https://github.com/your-username/petrol-station-management.git
2. Navigate to the project directory:
  cd petrol-station-management
3. Start the XAMPP server and place the project folder in the htdocs directory.
4. Import the database:
5. Copy the psms_db.db file to the appropriate directory.
  Access the application in a web browser:
  http://localhost/petrol-station-management/

## Usage
Login: Use the admin credentials:
-Username: admin
-Password: admin123
Navigate through the dashboard to:
-Manage customer and fuel records.
-Track sales and payments.
-Generate reports.

## Database Structure
The project uses an SQLite database with the following tables:
-user_list: Admin and cashier details
-petrol_type_list: Fuel types and prices
-customer_list: Customer information
-transaction_list: Transactions and sales
-debt_list: Outstanding payments
-payment_list: Payment records

## Conclusion
This project successfully delivers a digital solution for petrol station management, offering practical insights into web development, database management, and software lifecycle processes. It ensures streamlined operations and user satisfaction.


