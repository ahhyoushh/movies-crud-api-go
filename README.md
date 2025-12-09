# 🎬 Movies CRUD API (Golang)

A simple **CRUD (Create, Read, Update, Delete) API** for managing movie records, built with **Go** and **gorilla/mux**.

[API Base url](https://movies-crud-api-go.onrender.com)
```bash
https://movies-crud-api-go.onrender.com
```
---

## 🧠 Overview
This project implements a RESTful API to manage movies. Users can:
- Add new movies
- Retrieve all or specific movies
- Update movie details
- Delete movies

The API uses `gorilla/mux` for routing and the standard Go library for JSON handling.

---

## 💡 Motivation
I created this project to:
- Practice building RESTful APIs in Go
- Understand efficient handling of CRUD operations
- Explore Go’s speed and simplicity for backend development

---

## ⚙️ Tech Stack
- **Golang**
- **gorilla/mux** (router)
- **JSON** handling via Go standard library
- **Postman / cURL** for testing APIs

---

## 📡 API Endpoints

| Method | Endpoint           | Description                  |
|--------|------------------|------------------------------|
| GET    | /movies           | Retrieve all movies          |
| GET    | /movies/{id}      | Retrieve a movie by ID       |
| POST   | /movies           | Add a new movie              |
| PUT    | /movies/{id}      | Update an existing movie     |
| DELETE | /movies/{id}      | Delete a movie by ID         |

---

## 📊 Sample Movie JSON
```json
{
  "id": "1",
  "isbn": "438227",
  "title": "Inception",
  "director": {
    "firstname": "Christopher",
    "lastname": "Nolan"
  }
}
