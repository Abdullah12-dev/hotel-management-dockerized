# 🏨 Hotel Management System (Dockerized MERN Stack)

## 1. 📘 Introduction

The **Hotel Management System** is a **MERN-stack** (MongoDB, Express, React, Node.js) web-based application designed to automate and simplify hotel operations. The application is divided into three main panels, each developed independently:

- **Admin Panel**
- **Receptionist Panel**


---

## 2. 📌 Project Overview

### 2.1 🎯 Project Goals

- Automate daily hotel operations.
- Enhance user experience for hotel guests.
- Streamline staff and admin workflows.
- Provide secure and robust data management.

### 2.2 ✨ Key Features

- Full CRUD for guests, rooms, bookings, and services.
- SMS notification and weather data API integration.
- Search and filtering capabilities in all relevant modules.

---

## 3. 📂 Modules and Features

### 3.1 🔐 Admin Panel

Tools for high-level hotel management and data integrity.

#### Features:
- Login / Recover Password
- Dashboard: Hotel stats (bookings, revenue, occupancy)
- **Staff Management**
  - Add/edit/delete staff
  - Assign roles
  - View performance metrics
- **Room Management**
  - Add/edit/delete rooms (single, deluxe, suite)
  - View availability
- **Service Management**
  - Manage services (spa, laundry, meals)
  - Pricing updates & service deactivation
- **Report Generation**
  - Generate/export booking/revenue/occupancy reports (PDF)
- **Third-party APIs**
  - SMS and weather integration
- **System Logs**
  - Track user activity (filterable)
- **Settings**
  - Policy configuration & notification preferences

### 3.2 💼 Receptionist Panel

Focuses on check-in/check-out, room assignment, and guest services.

#### Features:
- Login
- **Guest Check-In**
  - Record guest info, assign rooms, generate invoices
- **Guest Check-Out**
  - Payment, mark room available
- **Booking Management**
  - CRUD operations, date/room/status filters
- **Search Guests**
  - Search by name, phone, room number
- **Room Allocation**
  - Assign rooms, manage room status
- **Guest Profile Management**
  - Edit guest data, view history
- **Service Requests**
  - Log & manage requests (meals, cleaning, etc.)
- **Notifications**
  - SMS reminders for check-in, offers
- **Weather Updates**
  - Real-time weather info for hotel location

---

## 4. 🐳 Running the Project with Docker

> **Prerequisites:**  
> - Docker  
> - Docker Compose

### 4.1 🧱 Build & Run Using Docker Compose

```bash
docker compose up --build
```

---

## 5. 🐳 Running the Project locally

### ✅ Backend

```bash
cd backend
npm install
npm start
```

### ✅ Frontend

```bash
cd frontend
npm install
npm start
```
