# Business Management System (BMS)

A web-based Business Management System designed to manage business operations through an admin panel. It helps organize customers, employees, products, inventory, sales, purchases, and suppliers in one place.

## Features

- Admin login and session management
- Dashboard with business statistics and sales charts
- Customer management
- Employee management
- Product and inventory management
- Sales and purchase management
- Supplier management
- Reports and activity logs
- PDF sales invoice generation
- Product image uploads

## Technologies Used

- PHP
- MySQL
- JavaScript
- HTML5
- CSS3
- TCPDF for PDF invoice generation

## Project Structure

```text
BMS/
├── admin/       # Admin panel and user interface
├── backend/     # PHP backend operations
└── tcpdf/       # PDF generation library
```

## Installation

1. Install XAMPP and start Apache and MySQL.
2. Clone or download this repository into your `htdocs` directory.
3. Create a MySQL database named `bms` using phpMyAdmin.
4. Import the required database tables and structure.
5. Open `backend/connection.php` and configure your database credentials.
6. Open the project in your browser:

   `http://localhost/BMS/admin/login.php`

## Database Configuration

Update the database settings in `backend/connection.php` according to your local environment.

## Purpose

This project demonstrates practical web development concepts, including CRUD operations, database integration, session-based authentication, inventory management, and PDF invoice generation.

## Author

Mohit Sharma

GitHub: https://github.com/mxhitsharmaa
