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
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/zidio/       # Core backend logic (controllers, services, models, etc.)
│   │   │   └── resources/                    # Configuration files (application.properties, etc.)
│   │   └── test/                             # Unit & Integration tests
│   ├── .gitignore
│   ├── .gitattributes
│   ├── mvnw / mvnw.cmd
│   ├── pom.xml                               # Maven dependencies and build config
│
├── frontend/
│   ├── index.html                            # Main HTML file
│   ├── style.css                             # CSS styling
│   ├── main.js                               # JavaScript logic
│
└── README.md                                 # Project overview (this file)

