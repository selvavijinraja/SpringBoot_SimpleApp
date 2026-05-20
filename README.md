# SpringBoot_SimpleApp

A simple full-stack web application built using **Spring Boot** for the backend and a basic frontend interface for displaying and managing products. This project was developed as part of my learning journey in Java Full Stack Development and demonstrates CRUD operations, REST APIs, and database integration using PostgreSQL.

---

## 🚀 Features

- Add Products
- View Products
- Update Product Details
- Delete Products
- REST API Integration
- PostgreSQL Database Connectivity
- Layered Spring Boot Architecture

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- PostgreSQL

### Frontend
- HTML
- CSS
- React

### Tools & Platforms
- Eclipse
- VS Code
- Postman
- Git & GitHub

---

## 📂 Project Structure

```bash
SpringBoot_SimpleApp/
│
├── ecom-proj/ecom-proj/    # Spring Boot backend
├── ecom-frontend/          # Frontend UI
├── Photos/                 # Screenshots
└── README.md
```

---

## ⚙️ Backend Setup

### 1️⃣ Navigate to Backend Folder

```bash
cd ecom-proj/ecom-proj
```

---

### 2️⃣ Configure PostgreSQL Database

Update the database configuration in:

```bash
src/main/resources/application.properties
```

Example configuration:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/ecom_db
spring.datasource.username=postgres
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

### 3️⃣ Run Spring Boot Application

```bash
mvn spring-boot:run
```

Backend server will start at:

```bash
http://localhost:8080
```

---

## ⚙️ Frontend Setup

### 1️⃣ Navigate to Frontend Folder

```bash
cd ecom-frontend
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Start Frontend Application

```bash
npm start
```

Frontend will run at:

```bash
http://localhost:5173
```

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/products` | Get all products |
| GET | `/product/{id}` | Get product by ID |
| POST | `/product` | Add new product |
| PUT | `/product` | Update product |
| DELETE | `/product/{id}` | Delete product |

---

## 📸 Screenshots

Sample photos are available in the `Photos` folder.

---

## 📖 Learning Outcomes

Through this project, I learned:

- Building REST APIs using Spring Boot
- Database integration with PostgreSQL
- CRUD operations using JPA & Hibernate
- Backend and frontend integration
- Project structure and dependency management using Maven
- GitHub project management

---

## ⭐ Acknowledgement

This project was built as part of my Spring Boot learning journey through tutorials, self-practice, and experimentation.