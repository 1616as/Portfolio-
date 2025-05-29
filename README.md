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
