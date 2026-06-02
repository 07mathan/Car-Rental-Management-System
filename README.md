🚗 Car Rental Management System

A web-based Car Rental Management System developed using PHP and MySQL that allows users to browse vehicles, check availability, make bookings, manage profiles, and submit testimonials. The system also includes a comprehensive admin panel for managing vehicles, brands, bookings, and users.

📌 Features
User Module
User Registration & Login
Browse Available Cars
Vehicle Details Page
Check Vehicle Availability
Online Car Booking
Booking History Management
Profile Management
Submit Testimonials
Contact Us Form
Secure Logout Functionality
Admin Module
Admin Authentication
Dashboard Overview
Vehicle Management
Vehicle Brand Management
Booking Management
New Bookings
Confirmed Bookings
Cancelled Bookings
User Management
Testimonial Management
Website Content Management
Vehicle Image Management
🛠️ Technology Stack
Frontend
HTML5
CSS3
Bootstrap
JavaScript
jQuery
Backend
PHP
Database
MySQL
Server
Apache (XAMPP/WAMP/LAMP)
📂 Project Structure
carrentalnew/
│
├── admin/
│   ├── dashboard.php
│   ├── create-brand.php
│   ├── edit-brand.php
│   ├── edit-vehicle.php
│   ├── confirmed-bookings.php
│   ├── canceled-bookings.php
│   └── includes/
│
├── includes/
│   └── config.php
│
├── index.php
├── car-listing.php
├── check_availability.php
├── contact-us.php
├── my-booking.php
├── profile.php
├── post-testimonial.php
├── my-testimonials.php
├── page.php
├── logout.php
│
└── assets/
⚙️ Installation Guide
1. Clone Repository
git clone https://github.com/yourusername/car-rental-management-system.git
2. Move Project

Copy the project folder into:

XAMPP

xampp/htdocs/

or

WAMP

wamp/www/
3. Create Database

Open phpMyAdmin and create a database:

carrental
4. Import Database

Import the provided SQL file into the database.

5. Configure Database Connection

Open:

includes/config.php

Update database credentials:

$host = "localhost";
$username = "root";
$password = "";
$dbname = "carrental";
6. Start Server

Start:

Apache
MySQL
7. Run Application
http://localhost/carrentalnew
👤 User Functionalities
View available vehicles
Search and browse cars
Check availability
Make bookings
View booking history
Manage profile
Submit reviews and testimonials
🔐 Admin Functionalities
Manage vehicle inventory
Manage brands
Manage bookings
Approve or cancel reservations
Manage users
View reports and statistics
Update vehicle images
📸 Screenshots

Add screenshots here:

screenshots/
├── homepage.png
├── vehicle-list.png
├── booking-page.png
├── admin-dashboard.png
🚀 Future Enhancements
Online Payment Gateway Integration
Email Notifications
SMS Alerts
Vehicle Availability Calendar
Advanced Search Filters
REST API Support
Mobile Application Integration
🤝 Contributing

Contributions are welcome.

Fork the repository
Create a feature branch
