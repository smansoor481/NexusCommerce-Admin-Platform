# NexusCommerce-Admin-Platform
"Nexus" signifies a powerful connection point — this title communicates that your system is the central hub connecting all aspects of e-commerce operations (products, users, orders, inventory) through a modern tech stack.

This project is a full-stack Admin Panel application for managing an e-commerce platform. It allows administrators to manage categories, products, users, and orders through a responsive frontend built with **React + Vite** and a secure, RESTful backend powered by **Spring Boot**.

---

## 📁 Project Structure

### Frontend (React + Vite)
- Folder: `ecom-frontend-5-main`
- Technologies: React, Vite, JavaScript, Axios, Tailwind (if used)
- Features:
  - Admin login (authentication)
  - Add/Edit/Delete Categories
  - Add/Edit/Delete Products
  - View Users and Orders
  - Dashboard view with statistics

### Backend (Spring Boot)
- Folder: `Ecom-proj1`
- Technologies: Spring Boot, Spring Data JPA, Hibernate, MySQL, Maven
- Features:
  - REST APIs for Products, Categories, Orders, and Users
  - JWT Authentication or session-based security (if configured)
  - Database integration via JPA/Hibernate

---

## 🚀 How to Run the Project


## 🚀 Getting Started

### ⚙️ Backend Setup (Spring Boot)

1. Navigate to the backend directory:
   ```bash
   cd backend
2. spring.datasource.url=jdbc:mysql://localhost:3306/nexuscommerce
spring.datasource.username=root
spring.datasource.password=your_password

3. ./mvnw spring-boot:run

4. Access the backend at: http://localhost:8080


💻 Frontend Setup (React + Vite)

1. cd frontend
2. npm install
3. npm run dev
4. http://localhost:5173



API endpoints overview

| Method | Endpoint           | Description          |
| ------ | ------------------ | -------------------- |
| POST   | /api/auth/login    | Admin login          |
| GET    | /api/products      | Fetch all products   |
| POST   | /api/products      | Add new product      |
| PUT    | /api/products/{id} | Update product by ID |
| DELETE | /api/products/{id} | Delete product by ID |
| GET    | /api/categories    | Fetch all categories |
| POST   | /api/categories    | Add new category     |


