# 🔐 Zidio Connect

Zidio Connect is a secure and scalable web application built using **Spring Boot**, designed to manage user authentication, data access, and business logic. It uses **JWT** for token-based security, **Spring Security** for role-based access control, **Spring Data JPA** for data persistence, and integrates with **MySQL** as the backend database.

---

## 🚀 Features

- ✅ User registration and login
- ✅ JWT-based authentication and authorization
- ✅ Role-based access control with Spring Security
- ✅ RESTful API structure
- ✅ MySQL database integration
- ✅ Maven-based project with layered architecture
- ✅ DevTools for hot reloads in development

---

## 🛠️ Tech Stack

| Tool/Framework       | Purpose                            |
|----------------------|------------------------------------|
| Java 17              | Programming Language               |
| Spring Boot          | Backend framework                  |
| Frontend     | HTML, CSS, JavaScript (or React, Vue, etc.) |
| Spring Security      | Authentication and Authorization   |
| JWT (jjwt)           | Token-based security               |
| Spring Data JPA      | ORM and database interaction       |
| MySQL                | Relational database                |
| Maven                | Build and dependency management    |

---

## 📁 Project Structure
zidio-connect/
├── backend/
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/com/example/zidio/ # Core backend logic
│ │ │ └── resources/ # Configuration files
│ │ └── test/ # Unit & Integration tests
│ ├── .gitignore
│ ├── .gitattributes
│ ├── mvnw / mvnw.cmd
│ ├── pom.xml # Maven dependencies
├── frontend/
│ ├── index.html # Main HTML
│ ├── style.css # Styling
│ ├── main.js # JavaScript logic
└── README.md # Project overview (this file)
