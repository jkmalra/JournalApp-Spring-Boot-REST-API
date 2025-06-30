# 📝 Journal Entry REST API (Spring Boot)

A simple RESTful API built with Spring Boot to perform basic CRUD operations on journal entries.  
This project is designed for learning backend development, REST principles, and as a base to integrate MongoDB, Spring Security, and other production-grade tools.

---

## 🚀 Features

- Create a journal entry
- Get all journal entries
- Get journal entry by ID
- Update journal entry by ID
- Delete journal entry by ID
- JSON request/response handling
- Tested using Postman

---

## 📦 Technologies Used

- Java 17+
- Spring Boot
- REST APIs
- Maven (build tool)
- Postman (API testing)

---

## 🧪 API Endpoints

| Method | Endpoint                  | Description               |
|--------|---------------------------|---------------------------|
| GET    | `/journal`                | Get all journal entries   |
| POST   | `/journal`                | Create a new entry        |
| GET    | `/journal/id/{myId}`      | Get entry by ID           |
| PUT    | `/journal/id/{id}`        | Update entry by ID        |
| DELETE | `/journal/id/{myId}`      | Delete entry by ID        |

---

## 📥 Sample JSON Request (POST / PUT)

```json
{
  "id": 1,
  "title": "First Entry",
  "content": "This is my first journal entry."
}
