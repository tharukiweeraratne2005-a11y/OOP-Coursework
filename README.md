# OOP-Coursework
# GearRentPro - Equipment Rental Management System

### Project Description
This is a professional photography equipment rental management system designed for a coursework submission. It handles branches, categories, equipment, and customer rentals with a dynamic login system.

### Default Login Credentials (DB Based)
You can use the following credentials to log into the system. These are stored in the `users` table:

* **Admin:** admin / Admin@123
* **Branch Manager:** manager_pan / Manager@123
* **Staff:** staff_pan / Staff@123

### Database Configuration
1. The project includes a database backup file named `database.sql` inside the ZIP.
2. Import this `database.sql` into your MySQL server to create the tables and load the sample data.
3. Ensure the database connection settings in `DBConnection.java` match your local MySQL credentials (username and password).

### Features
- **Dynamic Login:** Validates users directly from the MySQL database.
- **Role-based Access:** Supports Admin, Branch Manager, and Staff roles.
- **Branch Management:** Kaluthra, Panadura, and Galle branches.
- **Inventory & Rentals:** Manage equipment categories, customers, and rental transactions.
