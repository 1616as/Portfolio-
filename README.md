# Institute Management System

This is a simple PHP-MySQL web application to manage student and faculty records in an institute. It supports user login, course management, and student registration.

## Features
- Add/view/edit/delete students and courses
- Login/logout system
- Admin dashboard

## Technologies Used
- PHP
- MySQL
- HTML, CSS

## How to Run
1. Import SQL file in XAMPP/phpMyAdmin
2. Run `index.php` from XAMPP localhost
<?php
// Simple connection test (replace with your DB credentials)
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "institute_db";

$conn = new mysqli($servername, $username, $password, $dbname);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}

echo "Connected successfully to Institute Management System database.";
?>
