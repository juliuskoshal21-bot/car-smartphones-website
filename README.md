# J&K Autotech — Car & Smartphone Dealership Management System

J&K Autotech is a web-based car and smartphone dealership management system developed for the Kenyan market. The platform allows customers to browse, search, filter, compare, and inquire about cars and smartphones available for sale.

The system also provides an administration dashboard for managing products, customers, inquiries, bookings, inventory, and sales information.

## 🚗📱 Project Overview

The system is designed to digitally improve the way a dealership displays and manages cars and smartphones while providing customers with an easy way to access product information online.

### Main Objectives

* Display available cars and smartphones online.
* Allow customers to search and filter products.
* Provide detailed product specifications and images.
* Allow customers to submit product inquiries.
* Provide request-to-buy/booking functionality.
* Allow administrators to manage dealership inventory.
* Manage customer inquiries and booking records.
* Store dealership information in a centralized database.

## ✨ Features

### Customer Features

* 🏠 Home page
* 🚗 Cars catalogue
* 📱 Smartphones catalogue
* 🔍 Product search
* 🎯 Product filtering
* 💰 Price display
* 📋 Product specifications
* 🖼️ Product images
* 👤 Customer registration
* 🔐 Customer login
* 💬 Product inquiries
* 📅 Request-to-buy/booking
* 📊 Product comparison
* 📱 Responsive design

### Admin Features

* 🔐 Secure admin login
* 📊 Admin dashboard
* ➕ Add cars
* ➕ Add smartphones
* ✏️ Edit products
* 🗑️ Delete/deactivate products
* 💰 Manage product prices
* 🖼️ Manage product images
* 📦 Manage inventory
* 👥 Manage customers
* 💬 Manage inquiries
* 📅 Manage bookings
* 💵 View sales records

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* PHP
* Laravel-compatible architecture can be added in future versions

### Database

* MySQL

### Development Environment

* XAMPP
* Visual Studio Code

### Additional Technology

* Python
* Flask
* REST API

## 📁 Project Structure

```text
car-smartphones-website/
│
├── index.php
├── login.php
├── register.php
├── logout.php
│
├── cars/
│   ├── index.php
│   ├── details.php
│   └── search.php
│
├── smartphones/
│   ├── index.php
│   ├── details.php
│   └── search.php
│
├── admin/
│   ├── dashboard.php
│   ├── login.php
│   ├── products.php
│   ├── add-product.php
│   ├── edit-product.php
│   ├── customers.php
│   ├── inquiries.php
│   ├── bookings.php
│   └── sales.php
│
├── config/
│   └── database.php
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│
├── python/
│   ├── app.py
│   └── requirements.txt
│
├── database.sql
├── README.md
└── .gitignore
```

## 🗄️ Database

The system uses MySQL to store information such as:

* Users
* Administrators
* Cars
* Smartphones
* Product categories
* Customer inquiries
* Bookings
* Sales
* Inventory

### Example Database

```text
jk_autotech
│
├── users
├── admins
├── products
├── cars
├── smartphones
├── inquiries
├── bookings
└── sales
```

## 💻 Installation Using XAMPP

### 1. Install XAMPP

Download and install XAMPP on your computer.

Start:

```text
Apache
MySQL
```

### 2. Clone the Repository

Open Command Prompt or Git Bash:

```bash
git clone https://github.com/juliuskoshal21-bot/car-smartphones-website.git
```

Move into the project:

```bash
cd car-smartphones-website
```

### 3. Move the Project to XAMPP

Copy the project folder to:

```text
C:\xampp\htdocs\
```

The final location should be:

```text
C:\xampp\htdocs\car-smartphones-website
```

### 4. Create the Database

Open:

```text
http://localhost/phpmyadmin
```

Create a database named:

```text
jk_autotech
```

Import:

```text
database.sql
```

### 5. Configure Database Connection

Open the database configuration file:

```text
config/database.php
```

Set the MySQL configuration according to your XAMPP installation.

Example:

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "jk_autotech";
```

### 6. Run the Website

Open your browser and visit:

```text
http://localhost/car-smartphones-website/
```

## 🔐 Admin Access

For development/testing, an administrator account can be created through the database.

Example:

```text
Email: admin@jkautotech.co.ke
Password: admin123
```

**Important:** Change the default password before deploying the system publicly.

## 🐍 Python Component

The project can optionally use Python to provide additional intelligent functionality such as:

* Product recommendations
* Price analysis
* Customer-product matching
* Simple analytics
* Future AI chatbot integration

The Python service can be implemented using Flask.

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask service:

```bash
python app.py
```

Example API:

```text
http://127.0.0.1:5000/
```

## 🔎 Product Search

Customers can search products using information such as:

* Product name
* Brand
* Model
* Category
* Price
* Year
* Specifications

Example:

```text
Toyota Prado
```

or:

```text
iPhone 16
```

## 📱 Responsive Design

The website is designed to work on:

* Desktop computers
* Laptops
* Tablets
* Android phones
* iPhones

## 🔒 Security Considerations

The system should implement:

* Password hashing
* User authentication
* Session management
* Input validation
* SQL injection protection
* Access control
* Secure database queries
* Admin authorization

Passwords should never be stored as plain text.

## 🚀 Future Improvements

Future versions may include:

* M-Pesa payment integration
* Online vehicle financing requests
* AI-powered product recommendations
* AI chatbot
* Email notifications
* SMS notifications
* Advanced sales analytics
* Customer reviews and ratings
* Wishlist functionality
* Multiple dealership branches
* Cloud deployment
* Laravel REST API
* Mobile application

## 🎓 Academic Project

This project is developed as an academic Information Technology project and demonstrates practical application of:

* Web development
* Database management
* Software engineering
* Authentication
* CRUD operations
* JavaScript programming
* PHP programming
* MySQL
* Python
* System analysis and design

## 👨‍💻 Developer

**Julius Koshal**

Information Technology Student
Maseno University
Kenya

## 📄 License

This project is intended for educational and demonstration purposes.

© 2026 J&K Autotech. All Rights Reserved.
