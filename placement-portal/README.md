# Placement Portal Website

A simple placement portal system using HTML, CSS, JavaScript, and PHP.

## Features
- Student Registration and Login
- Dashboard Page
- Simple PHP-MySQL Backend

## Requirements
- PHP Server (XAMPP/WAMP)
- MySQL Database

## Setup
1. Import the SQL table:
```sql
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100) UNIQUE,
  password VARCHAR(255)
);
```
2. Run on `localhost`.

## Author
Your Name