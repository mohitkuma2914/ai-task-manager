# AI Task Manager

AI Task Manager is a backend application built using **Java Spring Boot** that helps manage tasks efficiently through REST APIs. The project follows a clean layered architecture including **Controller, Service, Repository, and Model layers**.

This project demonstrates practical implementation of **Spring Boot, REST APIs, PostgreSQL integration, and Docker containerization**.

---

# 🚀 Features

* Create new tasks
* Update existing tasks
* Delete tasks
* Fetch all tasks
* REST API based architecture
* PostgreSQL database integration
* Docker support

---

# 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring Data JPA
* Maven

### Database

* PostgreSQL

### Tools

* Docker
* Git
* GitHub

---

# 📂 Project Structure

```id="pjw1hv"
AI-Task-Manager-main
│
├── .mvn/                     # Maven wrapper files
├── frontend/                 # Frontend UI (if applicable)
│
├── src/
│   ├── main/
│   │   ├── java/com/taskmanager/
│   │   │   ├── config/       # Configuration classes
│   │   │   ├── controller/   # REST controllers
│   │   │   │   └── TaskController.java
│   │   │   ├── model/        # Entity classes
│   │   │   ├── repository/   # JPA repositories
│   │   │   ├── service/      # Business logic
│   │   │   └── AiTaskManagerApplication.java
│   │   │
│   │   └── resources/
│   │       ├── static/       
│   │       ├── application.properties
│   │       ├── application-local.properties
│   │       └── application-prod.properties
│   │
│   └── test/
│       └── java/com/taskmanager/
│           └── AiTaskManagerApplicationTests.java
│
├── target/                   # Compiled files
├── Dockerfile                # Docker configuration
├── pom.xml                   # Maven dependencies
├── .gitignore
└── README.md
```

---
