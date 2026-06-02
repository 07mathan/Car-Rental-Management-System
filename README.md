
# 🚗 Car Rental Management System

A web-based Car Rental Management System developed using PHP and MySQL. The platform allows users to seamlessly browse vehicles, check real-time availability, make bookings, manage profiles, and submit testimonials. It also includes a comprehensive Admin Panel for backend administration.


## 📌 Features

### User Module
* **Authentication:** User registration, secure login, and logout functionality.
* **Vehicle Discovery:** Browse available cars, search by criteria, and view detailed vehicle specifications.
* **Booking System:** Check real-time vehicle availability and place bookings online.
* **Dashboard:** View booking history, manage personal profiles, and update passwords.
* **Engagement:** Submit reviews, testimonials, and contact the team via a built-in contact form.

### Admin Module
* **Admin Authentication:** Secure admin dashboard access.
* **Overview Dashboard:** Total snapshots of metrics (cars, users, bookings).
* **Inventory Management:** Create, update, and manage vehicle listings and brands.
* **Booking Moderation:** Review new bookings to confirm or cancel reservations.
* **User & Content Management:** Manage registered users, approve customer testimonials, and update dynamic page content.

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, CSS3, Bootstrap, JavaScript, jQuery
* **Backend:** PHP
* **Database:** MySQL
* **Server Environment:** Apache (XAMPP / WAMP / LAMP)

---

## 📂 Project Structure

```text
carrentalnew/
│
├── admin/
│   ├── includes/
│   ├── dashboard.php
│   ├── create-brand.php
│   ├── edit-brand.php
│   ├── edit-vehicle.php
│   ├── confirmed-bookings.php
│   └── canceled-bookings.php
│
├── includes/
│   └── config.php
│
├── assets/
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
├── vehicle-details.php
└── logout.php

```

---

## ⚙️ Installation Guide

### 1. Clone the Repository

```bash
git clone [https://github.com/07mathan/Car-Rental-Management-System.git](https://github.com/07mathan/Car-Rental-Management-System.git)

```

### 2. Move the Project

Copy the cloned project folder into your local server environment's root directory:

* **XAMPP:** `xampp/htdocs/`
* **WAMP:** `wamp/www/`

### 3. Setup the Database

1. Open your browser and navigate to **phpMyAdmin** (`http://localhost/phpmyadmin`).
2. Create a new database named `carrental`.
3. Import the provided **SQL file** located in the repository root into your newly created database.

### 4. Configure Database Connection

Open `includes/config.php` and update your local database credentials if they differ from the default setup:

```php
$host = "localhost";
$username = "root";
$password = "";
$dbname = "carrental";

```

### 5. Run the Application

1. Start the **Apache** and **MySQL** modules from your XAMPP/WAMP control panel.
2. Open your browser and navigate to:
`http://localhost/carrentalnew`

---

## 🚀 Future Enhancements

* 💳 **Payment Gateway:** Integration of online payment options (Stripe/PayPal).
* 📧 **Notifications:** Automated email confirmations and SMS alerts for updates.
* 📅 **Availability Calendar:** Interactive visual calendar interface on vehicle pages.
* 🔍 **Advanced Filtering:** Better filtering capabilities (price range, fuel type, transmission).
* 📱 **Mobile App/API:** REST API support for extending into mobile applications.

```

```
