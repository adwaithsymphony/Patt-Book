Patt Book
Smart Expense Tracker and Financial Analytics System

Patt Book is a Java-based desktop expense tracking application developed using Java Swing, JDBC, and MySQL. The application helps users manage personal expenses efficiently through expense categorization, monthly analytics, report generation, and secure authentication.

Features
User Registration & Login
Add / Update / Delete Expenses
Expense Categorization
Monthly Expense Summaries
Expense Filtering
Financial Analytics
Report Export (CSV/TXT)
Java Swing GUI
MySQL Database Integration
Technology Stack
Frontend
Java Swing
Backend
Core Java
Database
MySQL
Database Connectivity
JDBC
Project Architecture
GUI Layer
    ↓
Business Logic Layer
    ↓
Database Layer
Database Tables
users
user_id
name
email
password
categories
category_id
category_name
expenses
expense_id
user_id
category_id
title
amount
expense_date
notes
Team Members & Responsibilities
Member	Responsibility
Team Lead	GUI, Integration, Debugging
Member 1	Database & JDBC
Member 2	Authentication Logic
Member 3	Expense CRUD Logic
Member 4	Analytics & Reports
Setup Instructions
1. Clone Repository
git clone <repo-link>
2. Open Project

Open in:

IntelliJ IDEA
Eclipse
VS Code
3. Configure MySQL

Create database:

CREATE DATABASE patt_book;

Run schema.sql.

4. Add JDBC Driver

Add MySQL JDBC Connector to project libraries.

5. Run Application

Run:

Main.java
Future Improvements
GUI enhancements
Charts and graphs
Budget tracking
PDF report export
Mobile application version
Cloud synchronization
Project Status

Currently under development as part of internship mini-project.

License

This project is developed for educational purposes.
