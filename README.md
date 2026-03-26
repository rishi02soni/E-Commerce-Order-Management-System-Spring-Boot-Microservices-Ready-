# 🚀 Smart Task Manager API (Spring Boot + JWT + MySQL)

A production-ready backend application built using **Spring Boot** that allows users to securely manage tasks with **JWT Authentication**. This project follows **industry-level architecture** and best practices.

---

## 📌 Project Overview

The Smart Task Manager is a RESTful API where users can:

- Register and Login securely 🔐  
- Create, update, and delete tasks 📝  
- Mark tasks as completed ✅  
- View all tasks 📃  

---

## 🧠 Tech Stack

- Java 17+
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Spring Data JPA (Hibernate)
- MySQL
- Maven
- Lombok

---

## 🏗️ Architecture

This project follows **Layered Architecture**:
Controller → Service → Repository → Database


---

## 📂 Project Structure
taskmanager/
│── src/main/java/com/taskmanager/
│ ├── controller/
│ ├── service/
│ ├── repository/
│ ├── entity/
│ ├── security/
│ ├── config/
│ ├── dto/
│ └── TaskManagerApplication.java
│
└── src/main/resources/
└── application.properties


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
git clone https://github.com/rishi02soni/taskmanager.git

cd taskmanager

---

### 2️⃣ Configure MySQL Database

Create a database:

Update `application.properties`:
spring.datasource.url=jdbc:mysql://localhost:3306/taskdb
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

jwt.secret=your_secret_key

---

### 3️⃣ Run the Application
mvn spring-boot:run


Application runs at:
http://localhost:8080


---

## 🔐 Authentication APIs

### ➤ Register User
POST /auth/register


Request Body:
{
"username": "rishi",
"password": "1234"
}

---

### ➤ Login User
POST /auth/login

Response:
JWT Token

---

## 📝 Task APIs

### ➤ Create Task
POST /tasks


### ➤ Get All Tasks
GET /tasks

### ➤ Update Task
PUT /tasks/{id}

### ➤ Delete Task
DELETE /tasks/{id}


---

## 🧪 Sample Task JSON
{
"title": "Learn Spring Boot",
"description": "Build backend project",
"completed": false
}


---

## 🔥 Key Features

- 🔐 JWT Authentication & Authorization  
- 🏗️ Clean Layered Architecture  
- 📦 RESTful API Design  
- ⚡ MySQL Database Integration  
- 🧩 Scalable Code Structure  
- 🧼 Clean & Maintainable Code  

---

## 🚀 Future Enhancements

- 👥 Role-Based Access (ADMIN / USER)  
- 📄 Pagination & Sorting  
- 🧾 Swagger API Documentation  
- 🐳 Docker Deployment  
- ⚡ Redis Caching  
- 🌐 Microservices Architecture  

---

## 🧠 Learning Outcomes

- Built scalable REST APIs using Spring Boot  
- Implemented JWT-based authentication  
- Designed layered backend architecture  
- Worked with relational databases using JPA/Hibernate  
- Improved code structuring and best practices  

---

## 📄 Resume Description

- Developed a secure Task Manager REST API using Spring Boot and MySQL  
- Implemented JWT-based authentication and authorization  
- Designed RESTful APIs using layered architecture  
- Integrated database operations using Spring Data JPA  

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub!
