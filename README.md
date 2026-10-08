# 🚗 Car Rental Management System

A web-based **Car Rental Management System** developed using **PHP and MySQL** that provides an easy and efficient platform for customers to browse vehicles, make rental bookings, manage their reservations, and complete payments.

The system also provides an **Admin Panel** for managing vehicles, users, bookings, returns, and other rental operations.

---

## 📌 Project Overview

The Car Rental Management System is designed to digitize and simplify the traditional car rental process.

Instead of managing vehicle availability, customer information, and bookings manually, the system provides a centralized web application where customers and administrators can perform their respective operations.

### 👤 Customer Side

Customers can:

- Register and create an account
- Login securely to the system
- Browse available vehicles
- View detailed information about cars
- Book a vehicle
- Check booking status
- Cancel bookings
- Make payments
- Submit feedback

### 🔐 Admin Side

Administrators can:

- Login through the Admin Panel
- Manage registered users
- Add new vehicles
- Update vehicle information
- Delete vehicles
- View customer bookings
- Approve bookings
- Manage vehicle returns
- Monitor rental operations

---

## ✨ Features

### 👤 User Features

- User Registration
- User Login
- User Authentication
- Vehicle Browsing
- Vehicle Details
- Online Car Booking
- Booking Status Tracking
- Booking Cancellation
- Payment Module
- Customer Feedback
- User Profile Management

### 🛠️ Admin Features

- Admin Authentication
- Admin Dashboard
- User Management
- Vehicle Management
- Add Vehicle
- Update Vehicle
- Delete Vehicle
- Booking Management
- Booking Approval
- Vehicle Return Management

### 🗄️ Database Features

- MySQL Database Integration
- Customer Data Management
- Vehicle Data Management
- Booking Records
- Payment Records
- User Records
- Feedback Records

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **PHP** | Backend development and server-side logic |
| **MySQL** | Database management |
| **HTML5** | Website structure |
| **CSS3** | Styling and layout |
| **JavaScript** | Client-side functionality |
| **Bootstrap** | Responsive UI components |
| **XAMPP** | Local development server |
| **Apache** | Web server |

---

## 🏗️ System Architecture

The application follows a simple web-based architecture:

```text
                ┌─────────────────────┐
                │       User          │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │    Web Interface    │
                │  HTML/CSS/Bootstrap  │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │        PHP          │
                │  Application Logic  │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │       MySQL         │
                │      Database       │
                └─────────────────────┘
