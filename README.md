# Hospital Management System using SQL & MySQL

## Project Overview
This project is a SQL-based Hospital Management System developed using MySQL. The system manages hospital operations including doctors, patients, appointments, prescriptions, billing, and lab reports.

The project demonstrates database design, normalization, triggers, stored procedures, joins, constraints, and healthcare data management.

---

## Features

- Patient Management
- Doctor Management
- Appointment Scheduling
- Prescription Management
- Billing System
- Lab Report Management
- Role-Based Doctor Access
- Revenue Analytics
- Trigger-Based Appointment Validation

---

## Database Tables

- Departments
- Doctors
- Patients
- Appointments
- Prescriptions
- Bills
- LabReports

---

## Technologies Used

- SQL
- MySQL
- MySQL Workbench

---

## SQL Concepts Used

- Primary Keys
- Foreign Keys
- Joins
- Aggregate Functions
- Stored Procedures
- Triggers
- Constraints
- Data Normalization
- GROUP BY
- Conditional Logic

---

## Advanced Functionalities

### Trigger
- Prevents duplicate doctor appointments
- Prevents scheduling appointments in past dates

### Stored Procedures
- Doctor role-based patient data access
- Monthly department revenue generation

---

## Dataset
The project uses CSV datasets containing:
- Doctors data
- Patients data
- Appointments
- Billing records
- Prescriptions
- Lab reports

---

## How to Run the Project

1. Open MySQL Workbench
2. Create a new database
3. Import the SQL file:
   ```sql
   hospital_management_system.sql
   ```
4. Execute the queries
5. Run stored procedures and test triggers

---

## Example Procedures

```sql
CALL VIEW_DOCTOR_DATA('doctor1','W3jzIANG');

CALL SP_MONTHLYREVENUE(2025,5);
```

---

## Project Highlights

- Designed relational database with 7+ interconnected tables
- Imported healthcare datasets from CSV files
- Implemented automation using triggers and procedures
- Built secure role-based data access system
- Generated department-wise revenue analytics
