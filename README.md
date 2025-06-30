# 🛒 E-MART: Electronics Shopping Web Application

**E-MART** is a full-stack web-based e-commerce application tailored for electronics shopping. Built with core Java technologies and modern frontend design principles, this project demonstrates a complete flow of an online shopping platform—from browsing products to placing orders and managing inventory.

---

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Key Features](#key-features)
- [Architecture](#architecture)
- [Folder Structure](#folder-structure)
- [Database Schema](#database-schema)
- [How to Run the Project](#how-to-run-the-project)
- [Screenshots](#screenshots)
- [Future Enhancements](#future-enhancements)
- [Author](#author)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 📌 Project Overview

E-MART simulates an electronics e-commerce portal. It has two major interfaces:
- **Customer Interface:** For users to register, log in, explore electronics items, add items to the cart, and place orders.
- **Admin Interface:** For managing products, categories, orders, and users.

The project uses the **MVC (Model-View-Controller)** pattern with **Servlets** handling the controller logic, **JSP** for the view layer, and **Oracle DB** for persistent storage. It is deployed on **Apache Tomcat** and uses JDBC for database interactions.

---

## 🧰 Tech Stack

### 🎨 Frontend
- **HTML5** — Page structure
- **CSS3** — Styling and layout
- **JavaScript** — Client-side interaction
- **Bootstrap 5** — Responsive and mobile-first UI design

### ⚙️ Backend
- **Java Servlets** — Handles business logic and HTTP requests
- **JSP (Java Server Pages)** — Dynamically renders HTML from server
- **JDBC** — Java Database Connectivity for DB operations
- **Oracle SQL** — Relational database for storing app data

### 🛠 Tools & Services
- Apache Tomcat 9/10
- Oracle SQL Developer
- Eclipse / IntelliJ IDEA
- Git & GitHub

---

## ✨ Key Features

### 🧑 User Panel
- Register & log in
- Browse electronics by category (e.g., Mobiles, Laptops, Accessories)
- Search products by name or brand
- Add items to the cart
- View cart summary and total price
- Checkout and place an order
- View past order history

### 👨‍💼 Admin Panel
- Admin authentication
- Add new products with images and details
- Edit or delete product listings
- Create or remove categories
- View all customer orders and track statuses

---


## 🏗️ Architecture

The project follows the **3-tier MVC architecture**:

Client (Browser)
↓
[View Layer] - JSP + HTML/CSS + JS
↓
[Controller Layer] - Java Servlets
↓
[Model Layer] - Java Beans + DAO (Database Access Objects)
↓
[Database Layer] - Oracle SQL



## 🚧 Future Enhancements
Integrate Razorpay / Stripe payment gateway

Mobile-friendly UI with improved responsiveness

Add user reviews and ratings for products

Implement pagination and filtering

Add email confirmation after registration and order


## 🙋 Author
Lekhansh Hedau
📧 lekhansh.hedau29@gmail.com
🔗 LinkedIn - https://www.linkedin.com/in/lekhansh-hedau-131005264/


## 🪪 License
This project is licensed under the MIT License.


## 🙏 Acknowledgements
Oracle Database Documentation

Bootstrap & W3Schools

Java Servlet & JSP API Docs

Stack Overflow Community

Freepik (for placeholder images)