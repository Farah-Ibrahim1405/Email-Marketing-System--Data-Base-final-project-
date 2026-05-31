# Email Subscribers Management System

A web-based Email Subscribers Management System built with PHP (PDO), MySQL, and styled with Bootstrap 5 and Custom CSS. This application allows users to join newsletter mailing lists while enabling employees/admins to manage, import, export, and update subscribers efficiently.  

## Features

### Public - User Side:
* Newsletter Registration: Users can easily fill out a subscription form to join specific mailing lists.  
* Secure Registration: Passwords are fully hashed using PASSWORD_BCRYPT before being stored in the database.  
* Pending Status: New self-subscribed users are placed under a Pending status waiting for admin action.  

### Employee - Admin Dashboard:
* Secure Authentication: Dedicated employee login portal to access management capabilities.  
* Subscriber Management: Fully-fledged CRUD operations (View, Add, Update status, and Delete subscribers).  
* Status Controls: Change subscriber status instantly (Active, Pending, Unsubscribed) using dynamic forms.  
* Bulk Data Operations:
  * Export to CSV: Download the entire subscribers list into a standard CSV file with one click.  
  * Import from CSV: Upload bulk subscriber lists via CSV files with automated handling for duplicate emails.  

## Tech Stack:

* Backend: PHP (OOP Data Objects - PDO)  
* Database: MySQL  
* Frontend: Bootstrap 5, Bootstrap Icons, Custom CSS gradients  

## Project Structure

```
├── style.css
├── add-subscriber.php
├── dashboard.php
├── db.php
├── delete-subscriber.php
├── export-csv.php
├── import-csv.php
├── index.php
└── logout.php
