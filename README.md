# 📚 SAMSTRACK API – Student Attendance Management System

## 📌 Project Overview

SAMSTRACK API is a backend REST API project developed using **Java and Spring Boot** for managing student attendance and academic information.

The application provides APIs to manage students, subjects, users, and attendance records through a structured backend architecture.

The project follows a layered architecture using **Controller, Service, DAO, Entity, Model, and Exception** packages.

---

## 🛠️ Technologies Used

- Java
- Spring Boot
- REST API
- Maven
- Spring Data JPA
- MySQL
- Git & GitHub

---

## 📂 Project Structure

```text
SAMSTRACK_API
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.tka.sams.api
│   │   │       ├── controller
│   │   │       ├── dao
│   │   │       ├── entity
│   │   │       ├── exceptions
│   │   │       ├── model
│   │   │       └── service
│   │   │
│   │   └── resources
│   │
│   └── test
│
├── pom.xml
└── README.md




## 🔹 Main Modules

### 👨‍🎓 Student Management

Provides functionality to manage student information.

- Add student
- Get student details
- Update student information
- Delete student information

### 📚 Subject Management

Provides functionality to manage subjects.

- Add subject
- Get subject details
- Update subject information
- Delete subject information

### 👤 User Management

Provides functionality to manage users.

- Add user
- Get user details
- Update user information
- Delete user information

### 📝 Attendance Management

Provides functionality to manage student attendance records.

- Add attendance record
- Get attendance records
- Update attendance records
- Delete attendance records

---

## 🏗️ Architecture

The project follows a layered backend architecture:

Client
   ↓
Controller
   ↓
Service
   ↓
DAO
   ↓
Database

### Controller Layer

Handles HTTP requests and API endpoints.

### Service Layer

Contains the business logic of the application.

### DAO Layer

Handles database-related operations.

### Entity Layer

Contains the application's database entities.

### Model Layer

Contains request/response related models.

### Exception Layer

Handles application-specific exceptions.

---

## 🚀 Key Features

- RESTful API architecture
- Student management
- Subject management
- User management
- Attendance record management
- Layered architecture
- Database integration
- Exception handling
- CRUD operations

---

## 🎯 Project Objective

The main objective of this project is to develop a backend system for managing student academic and attendance-related information.

This project helped in gaining practical experience with:

- Java
- Spring Boot
- REST APIs
- CRUD operations
- Layered architecture
- Database connectivity
- JPA
- Exception handling
- Backend application development

---

## ▶️ How to Run the Project

1. Clone the repository.
2. Open the project in IntelliJ IDEA or another Java IDE.
3. Configure the database connection in the application configuration.
4. Make sure Maven dependencies are installed.
5. Run `SamsTrackApplication.java`.
6. Test the APIs using Postman or Swagger UI.

---

## 📌 API Modules

| Module | Purpose |
|---|---|
| Student | Manage student information |
| Subject | Manage subjects |
| User | Manage users |
| Attendance | Manage attendance records |

---

## 📁 Project Files

The project contains the complete Spring Boot source code, including controllers, services, DAO classes, entities, models, exception handling, and application configuration.

---

## 👤 Author

**Asmita Gadekar**

Java Developer | Spring Boot | REST API | SQL

---

⭐ If you found this project useful, feel free to explore the source code and APIs.
