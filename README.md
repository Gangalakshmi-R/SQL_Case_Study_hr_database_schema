# HR Database Schema – SQL Project

This repository contains a SQL script named `hr_database_schema.sql`, which is part of a database-related case study.

## 📊 Project Overview

This SQL project sets up a relational database schema for a fictional company, focusing on locations, departments, and job roles. It uses best practices in database design including normalization and relational integrity.

### 🧱 Tables and Relationships

- **LOCATION**: Stores city names with unique `Location_ID`s.
- **DEPARTMENT**: Contains department details and links to LOCATION via `Location_Id`.
- **JOB**: Holds job titles mapped to `Job_ID`s.

### 🔄 Features

- Primary and foreign key constraints for data consistency.
- Insert statements to pre-populate tables with sample data.
- Structured for future queries, HR reports, or departmental analysis.

## 📁 Contents

- `hr_database_schema.sql`: The main SQL script containing schema and data.

## 🛠️ Requirements

To run this script, you will need:
- A relational database system, such as:
  - MySQL
  - PostgreSQL
  - SQLite
  - Microsoft SQL Server

## 🚀 Usage

1. Open your SQL client or CLI.
2. Connect to your target database.
3. Run `hr_database_schema.sql` to create and populate the schema.

### Example (using MySQL CLI):
```bash
mysql -u username -p database_name < "hr_database_schema.sql"
```

## 📌 Notes

- Review the script before running to understand its impact on your DB.
- Additional tables or logic may be present beyond the initial excerpt.

## 📄 License

This project is provided for educational or demonstration purposes. Please check with your instructor or organization for usage guidelines.
