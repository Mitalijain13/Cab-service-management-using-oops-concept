# 🚖 Cab Management & Booking System

## 📌 Overview

The **Cab Management & Booking System** is a software application designed to simulate a real-world ride-booking platform. It allows users to select different types of cabs based on pricing, choose pickup and drop locations, and manage bookings efficiently.

The system is built using **Object-Oriented Programming (OOP)** principles and integrates **SQL database** support for storing and retrieving user and booking data.

---

## 🚀 Features

* 🚗 **Multiple Cab Categories**
  Users can choose from different types of cabs (e.g., Mini, Sedan, SUV) with varying pricing models.

* 📍 **Location-Based Booking**
  Users can input pickup and drop locations to calculate fares.

* 💰 **Dynamic Pricing Logic**
  Fare is calculated based on distance, cab type, and pricing rules.

* 🧾 **Booking Management**
  Allows users to create, view, and manage ride bookings.

* 🗄️ **Database Integration (SQL)**
  Stores user details, booking history, and cab information in a structured database.

* 🔁 **Reusable & Modular Design**
  Implemented using OOP concepts for scalability and maintainability.

---

## 🛠️ Technologies Used

* **Programming Language:** (e.g., Python / Java)
* **Database:** SQL (MySQL / PostgreSQL / SQLite)
* **Concepts Used:**

  * Object-Oriented Programming (OOP)

    * Classes & Objects
    * Inheritance
    * Encapsulation
    * Polymorphism
  * Database Management
  * CRUD Operations

---

## 🧩 System Design

### Key Classes:

* **User Class** → Manages user details
* **Cab Class** → Defines cab types and pricing
* **Booking Class** → Handles ride bookings
* **Database Class** → Manages SQL operations

---

## ⚙️ How It Works

1. User enters details and selects pickup & drop location
2. System displays available cab options with prices
3. User selects preferred cab
4. Fare is calculated dynamically
5. Booking is confirmed and stored in the SQL database

---

## 📊 Database Structure (Example)

* **Users Table**

  * user_id
  * name
  * contact

* **Cabs Table**

  * cab_id
  * cab_type
  * price_per_km

* **Bookings Table**

  * booking_id
  * user_id
  * cab_id
  * pickup_location
  * drop_location
  * fare

---

## 🎯 Future Enhancements

* Integration with maps for real-time distance calculation
* Payment gateway integration
* Driver allocation system
* Admin dashboard

---



## 👨‍💻 Author

Developed by **Mitali Jain**

---
