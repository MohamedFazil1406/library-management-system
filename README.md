# 📚 Library Management System – Spring Boot REST API

A simple **Library Management System** built using **Java and Spring Boot**, designed to demonstrate RESTful API development, clean project structure, and backend best practices.

---

## 🚀 Features

- 📖 Manage Books (Add, Update, Delete, View)
- 👤 Manage Library Members
- 🔍 Search books by **title**
- 🔍 Search books by **author**
- 🌐 RESTful APIs with proper HTTP status codes
- 🧱 Clean layered architecture (Controller, Service, Model)
- ⚡ Java Streams for filtering and searching
- 🪵 SLF4J logging for debugging and monitoring

---

## 🛠 Tech Stack

- **Java**
- **Spring Boot**
- **Spring MVC**
- **Maven**
- **Java Streams**
- **SLF4J (Logging)**

---


---

## 🔗 API Endpoints

### 📘 Books

| Method | Endpoint | Description |
|------|---------|-------------|
| GET | `/books` | Get all books |
| GET | `/books/{id}` | Get book by ID |
| POST | `/books` | Add a new book |
| PUT | `/books/{id}` | Update a book |
| DELETE | `/books/{id}` | Delete a book |


---

### 👤 Members

| Method | Endpoint | Description |
|------|---------|-------------|
| GET | `/members` | Get all members |
| POST | `/members` | Add a member |
| PUT | `/members/{id}` | Update member |
| DELETE | `/members/{id}` | Delete member |

---

## ▶️ How to Run the Project

### Prerequisites
- Java JDK 21 (or compatible)
- Maven
- IntelliJ IDEA / VS Code

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/library-management-system.git

# Navigate to project directory
cd library-management-system

# Build the project
mvn clean install

# Run the application
mvn spring-boot:run


