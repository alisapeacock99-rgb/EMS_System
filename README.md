#Employee Management System (EMS)

## Overview

The **Employee Management System (EMS)** is a desktop application developed in **Java** using **Java Swing** for the graphical user interface and **Apache Derby Database** for data storage. The system is designed to help organizations efficiently manage employee records, departments, and payroll information through a centralized platform.

The application provides a user-friendly dashboard that allows administrators to perform CRUD (Create, Read, Update, Delete) operations on employees, departments, and payroll records while maintaining organized and accessible company data.

---

# Features

## Employee Management

* Add new employee records.
* View all employees stored in the database.
* Update employee information.
* Delete employee records.
* Store employee details including:

  * Employee ID
  * Full Name
  * Department
  * Role/Position
  * Phone Number
  * Email Address

## Department Management

* Create and manage company departments.
* View department records.
* Update department information.
* Remove departments when necessary.

## Payroll Management

* Add payroll records for employees.
* Store salary information.
* Record payroll payment dates.
* Update payroll details.
* Delete payroll records.

## Dashboard Interface

* Centralized navigation system.
* Easy access to:

  * Employee Management
  * Department Management
  * Payroll Management
* Simple and intuitive user experience.

---

# Technologies Used

## Programming Language

* Java

## User Interface

* Java Swing

## Database

* Apache Derby (Java DB)

## Database Connectivity

* JDBC (Java Database Connectivity)

## Development Environment

* Apache NetBeans IDE

---

# System Architecture

The project follows an Object-Oriented Programming (OOP) structure consisting of:

## Model Layer

Represents the application's data objects.

### Classes

* `Person`
* `Employee`
* `Department`
* `Payroll`

## Data Access Layer (DAO)

Handles communication between the application and the database.

### DAO Classes

* `EmployeeDAO`
* `DepartmentDAO`
* `PayrollDAO`

These classes provide:

* Create operations
* Read operations
* Update operations
* Delete operations

## Database Layer

Responsible for database connectivity and table management.

### Database Classes

* `DBConnection`
* `CreateTables`
* `InsertEmployee`
* `ViewEmployees`

## Presentation Layer

Java Swing forms used to interact with users.

### GUI Forms

* DashboardForm
* EmployeeForm
* DepartmentsForm
* PayrollForm

---

# Project Structure

```text
EMS_SYSTEMs/
│
├── src/
│   └── com/
│       └── ems/
│           ├── dao/
│           │   ├── EmployeeDAO.java
│           │   ├── DepartmentDAO.java
│           │   └── PayrollDAO.java
│           │
│           ├── database/
│           │   ├── DBConnection.java
│           │   ├── CreateTables.java
│           │   └── Database Test Files
│           │
│           ├── gui/
│           │   ├── DashboardForm.java
│           │   ├── EmployeeForm.java
│           │   ├── DepartmentsForm.java
│           │   └── PayrollForm.java
│           │
│           └── model/
│               ├── Person.java
│               ├── Employee.java
│               ├── Department.java
│               └── Payroll.java
│
└── EMSDB/
    └── Derby Database Files
```

---

# System Workflow

## 1. Launch Application

The user starts the application and is presented with the main dashboard.

## 2. Employee Management

Users can:

* Add employee records
* View employee information
* Update employee details
* Delete employees

## 3. Department Management

Users can:

* Add departments
* View department information
* Update department records
* Remove departments

## 4. Payroll Management

Users can:

* Record payroll information
* Manage employee salaries
* Track payment dates
* Update payroll records

## 5. Database Storage

All information is securely stored in the Apache Derby database and retrieved through JDBC connections.

---

# Learning Outcomes

This project demonstrates:

* Object-Oriented Programming (OOP)
* Java Swing GUI Development
* Database Design and Management
* JDBC Connectivity
* CRUD Operations
* DAO (Data Access Object) Design Pattern
* Layered Application Architecture
* Data Validation and Record Management

---

# Future Enhancements

* User Authentication and Login System
* Role-Based Access Control (Admin/HR/Manager)
* Employee Attendance Tracking
* Leave Management System
* Performance Evaluation Module
* Payroll Calculations and Tax Deductions
* Report Generation (PDF/Excel)
* Search and Filtering Functionality
* Data Backup and Recovery
* Cloud Database Integration

---

#  Author
-> Alisa Peacock
* Employee Management System (EMS)

A Java desktop application developed to demonstrate employee administration, department management, payroll processing, database integration, and Object-Oriented Programming principles using Java Swing, JDBC, and Apache Derby Database.
