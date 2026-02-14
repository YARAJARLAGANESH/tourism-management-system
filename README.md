# 🌍 Tourism Management System

A web-based Tourism Management System developed using PHP and MySQL.  
This project allows users to explore tourism packages and enables admin to manage bookings, users, and system settings.

---

## 🚀 Features

- User Registration & Login
- Admin Dashboard
- Manage Tourism Packages
- Manage Users
- Booking System
- Secure Authentication
- Database-driven dynamic content

---

## 🛠️ Technologies Used

- PHP (Core PHP - OOP)
- MySQL
- HTML5
- CSS3
- JavaScript
- XAMPP (Apache + MySQL)

---

## 💻 Installation Guide (Local Setup)

### Step 1: Install XAMPP
Download and install XAMPP.

### Step 2: Start Services
Open XAMPP Control Panel and start:
- Apache
- MySQL

### Step 3: Move Project
Copy project folder to:

### Step 4: Create Database
1. Open: http://localhost/phpmyadmin
2. Create database:

### Step 5: Import Database
1. Click the created database
2. Go to Import
3. Upload the provided `.sql` file
4. Click Go

### Step 6: Configure Database
Open:
or configuration file and ensure:

```php
define('DB_SERVER',"localhost");
define('DB_USERNAME',"root");
define('DB_PASSWORD',"");
define('DB_NAME',"tourism_db");

###Step 7: Run Project
Open browser:
http://localhost/tourism
http://localhost/tourism/admin

## 🔐 Admin Access

Administrator Credentials:

- **Username:** ADMIN  
- **Password:** ADMIN0906  

⚠ It is recommended to change the default credentials after first login.

