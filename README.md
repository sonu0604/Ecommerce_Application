# 🛒 E-Commerce Application

![Java](https://img.shields.io/badge/Backend-Java-orange)
![Spring Boot](https://img.shields.io/badge/Framework-SpringBoot-green)
![React](https://img.shields.io/badge/Frontend-React-blue)
![MySQL](https://img.shields.io/badge/Database-MySQL-lightblue)
![Architecture](https://img.shields.io/badge/Architecture-MVC-purple)

A **Full-Stack E-Commerce Web Application** built using **React.js, Spring Boot, and MySQL** that allows users to browse products, view product details, and perform purchase-related operations.

The application also provides **admin product management functionality with complete CRUD operations**, enabling efficient product management.

---

# 📌 Project Overview

This project demonstrates the development of a **complete full-stack web application**.

The platform allows users to:

- Browse products available in the store
- View product details
- Search and filter products
- Interact with backend APIs

Administrators can:

- Add new products
- Update product information
- Delete products
- Manage product inventory

The project follows **best practices like modular MVC architecture**, making the codebase **structured, scalable, and maintainable**.

---

# 🏗️ Application Architecture

The backend follows **MVC (Model-View-Controller) architecture** to separate responsibilities within the application.

```
Client (React.js)
       ↓
REST API (Spring Boot Controllers)
       ↓
Service Layer (Business Logic)
       ↓
Repository Layer (Database Access)
       ↓
MySQL Database
```

This architecture improves:

- Code organization
- Maintainability
- Scalability
- Separation of concerns

---

# ⚙️ Tech Stack

## Backend
- Java
- Spring Boot
- Spring Data JPA
- RESTful APIs

## Frontend
- React.js
- Axios / Fetch API
- HTML
- CSS
- JavaScript

## Database
- MySQL

## Tools
- Git
- GitHub
- Postman

---

# ✨ Features

## 👤 User Features
- Browse product catalog
- View product details
- Search products
- Filter products by category
- Interactive UI built with React

## 🛠️ Admin Features
- Add new products
- Update existing products
- Delete products
- Manage product inventory

## 🔗 Backend Features
- RESTful API design
- Modular MVC architecture
- Structured service and repository layers
- MySQL database integration

---

# 🗄️ Database Design

The application uses a **normalized MySQL database** to store product data efficiently.

### Product Table Structure

| Field | Description |
|------|-------------|
| id | Unique product identifier |
| name | Name of the product |
| price | Product price |
| category | Product category |
| description | Product details |
| inventory | Available stock quantity |

This structure ensures **efficient data storage and retrieval**.

---

# 🔌 REST API Endpoints

### Product APIs

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/products` | Retrieve all products |
| GET | `/products/{id}` | Retrieve product by ID |
| POST | `/products` | Add new product |
| PUT | `/products/{id}` | Update product |
| DELETE | `/products/{id}` | Delete product |

---

# 📷 Project Screenshots

<p align="center">
  <img src="https://github.com/sonu0604/Ecommerce_Application/blob/635eb7a04349be16fbe9ef5a2bb1460038094b6f/Screenshot%202026-03-06%20012526.png" width="45%" />
  <img src="https://github.com/sonu0604/Ecommerce_Application/blob/635eb7a04349be16fbe9ef5a2bb1460038094b6f/Screenshot%202026-03-06%20012835.png" width="45%" />
</p>

<p align="center">
<b>Product Listing Page</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>Product Details Page</b>
</p>

<p align="center">
  <img src="https://github.com/sonu0604/Ecommerce_Application/blob/635eb7a04349be16fbe9ef5a2bb1460038094b6f/Screenshot%202026-03-06%20012944.png" width="45%" />
  <img src="https://github.com/sonu0604/Ecommerce_Application/blob/635eb7a04349be16fbe9ef5a2bb1460038094b6f/Screenshot%202026-03-06%20012717.png" width="45%" />
</p>

<p align="center">
<b>Product Search / Filter</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>Admin Product Management</b>
</p>

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Building **full-stack web applications**
- Developing **REST APIs using Spring Boot**
- Implementing **MVC architecture**
- Integrating **React frontend with backend APIs**
- Designing **normalized MySQL databases**
- Managing code using **Git and GitHub**

---

# 📈 Future Improvements

Possible enhancements for this project include:

- User authentication with JWT
- Shopping cart functionality
- Order management system
- Payment gateway integration
- Admin dashboard analytics

---

# 👨‍💻 Author

**Shashank Ramchandra Pawal**

💻 Passionate about **Java, Backend Development, and Full-Stack Applications**

---

⭐ If you like this project, consider **starring the repository**.
