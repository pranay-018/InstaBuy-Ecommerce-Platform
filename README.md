# InstaBuy - Monolithic E-commerce Platform

## 🚀 Objective

InstaBuy is a monolithic e-commerce platform designed to deliver a seamless shopping experience for customers and a robust order management system for administrators. It centralizes product browsing, cart handling, secure payments, order tracking, admin tools, and analytics in one platform.

---

## 🧩 Problem Statement

To build a reliable and efficient e-commerce Order Management System (OMS) that includes:

- Centralized customer, product, and order data.
- Seamless product browsing and cart experience.
- JWT-based secure authentication.
- Admin functionalities like analytics dashboard and role assignment.

---

## 🗂️ Data Models

### ✅ Customer Data
- Name, email, phone, DOB, login credentials.

### 🛍 Product Data
- Name, description, price, category, image (BLOB).

### 📦 Order Data
- Order ID, customer ref, date, total, delivery status.

### 🛒 Cart & Items
- Cart sessions, cart ID, product ID, quantity, price.

### ⭐ Reviews
- Product reviews with rating, comments, timestamps.

### 💳 Transaction
- Transaction ID, order ID, amount, status.

### 🔐 Auth & Admin
- JWT-based authentication and admin controls.

---

## ⚙️ Tech Stack

| Layer      | Technology                         |
|------------|------------------------------------|
| Backend    | Java, Spring Boot, Spring Data JPA |
| Frontend   | React or Angular                   |
| Database   | MySQL                              |
| API        | RESTful APIs                       |
| Security   | JWT (JSON Web Tokens)              |

---

## 📁 Folder Structure

- `/backend` – Spring Boot source code.
- `/frontend` – React or Angular app.
- `/database` – SQL schema and seed data.
- `/docs` – Architecture diagrams and documentation.

---

## 🔐 Authentication

JWT token-based authentication is implemented for secure access and role management.

---

## 🛠 Features

- User registration & login
- Product catalog with image support
- Cart & checkout flow
- Order tracking
- Transaction management
- Review system
- Admin dashboard with analytics

---

## 🧪 Future Enhancements

- Email/SMS notification service
- Coupon and discount system
- Microservices architecture migration
- CI/CD Integration

---

## 📜 License

This project is licensed under the MIT License.
