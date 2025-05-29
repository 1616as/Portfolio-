# Sanitation X-Press Management System

An internal tool to manage sanitation workers, their schedules, and request status tracking.

## 🛠 Technologies Used
- HTML
- CSS
- PHP
- MySQL

## 🔑 Features
- Assign tasks to workers
- Track completion status
- Admin reporting panel

## 📁 Sample Code Snippet
```php
<?php
$query = "SELECT * FROM tasks WHERE status='pending'";
$result = mysqli_query($conn, $query);
?>
