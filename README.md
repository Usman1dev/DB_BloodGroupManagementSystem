# DB_BloodGroupManagementSystem


## Group Members
- **Muhammad Usman Khan** (241797)
- **Rafiullah** (241926)

## Project Title
**Blood Bank Management System (BBMS)**

## Description
The Blood Bank Management System is a Java-based desktop application built using Apache NetBeans 25 and JDK 23, backed by a Microsoft SQL Server database. It facilitates the management of blood donations, inventory, donors, patients, and staff. The system enables real-time updates, tracks transactions, handles blood requests, and supports campaign and appointment scheduling.

## Setup Instructions

### Prerequisites
- Java JDK 23
- Apache NetBeans 25
- Microsoft SQL Server Management Studio (SSMS)
- SQL Server running locally

### Step 1: Database Setup
1. Open SQL Server Management Studio (SSMS).
2. Run the `BBMS.sql` script to create the database and tables and populate the database with sample data.

### Step 2: Java Project Setup
1. Open the project in Apache NetBeans 25.
2. Ensure JDK 23 is set as the active Java platform.
3. Update your database connection string in the Java code (`DatabaseQueries.java`) to point to your local SQL Server instance.
4. Build and run the project.

### Step 3: Running Sample Queries
- Use the buttons in the GUI to perform the following actions:
  - View Donor Records
  - Insert New Blood Requests
  - Manage Inventory and Transactions
  - Generate Reports for Campaigns, Feedback, Appointments, and more

## Bonus: Frontend GUI
The project includes a complete frontend built using Java Swing, integrated into the NetBeans platform. The GUI allows users to:
- Manage all entities (Donors, Patients, Staff, etc.)
- View and execute operations using buttons linked to SQL queries
- Navigate the system with an intuitive interface

---

© 2025 Blood Bank Management System Projectss
