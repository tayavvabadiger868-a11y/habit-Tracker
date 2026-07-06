# 🔥 Habit Tracker

A simple full-stack Habit Tracker application built using **React**, **Express.js**, **SQLite**, and **better-sqlite3**. It allows users to create habits, view all habits, and delete habits.

---

## 📂 Project Structure

```
project/
│
├── backend/
│   ├── index.js
│   ├── package.json
│   └── data.db
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── main.jsx
│   └── package.json
│
└── postman/
    ├── Habit-Tracker-API.postman_collection.json
    └── Habit-Tracker.postman_environment.json
```

---

## 🚀 Technologies Used

- React + Vite
- Express.js
- Node.js
- SQLite
- better-sqlite3
- CORS

---

## ✨ Features

- Add a new habit
- View all habits
- Delete a habit
- Store data in SQLite database
- REST API
- Postman Collection Included

---

## 📦 Backend Setup

Navigate to the backend folder.

```bash
cd backend
```

Start the server.

```bash
node index.js
```

The server runs on:

```
http://localhost:5000
```

---

## 💻 Frontend Setup

Navigate to the frontend folder.

```bash
cd frontend
```

Start the React application.

```bash
npm run dev
```

The frontend runs on:

```
http://localhost:5173
```

---

## 📌 API Endpoints

### Get All Habits

```
GET /habits
```

---

### Add Habit

```
POST /habits
```

Request Body

```json
{
  "name": "Drink Water"
}
```

---

### Delete Habit

```
DELETE /habits/:id
```

Example

```
DELETE /habits/1
```

---

## 🗄 Database

SQLite database file:

```
data.db
```

Table:

### habits

| Column | Type |
|---------|------|
| id | INTEGER |
| name | TEXT |
| created_at | TEXT |

---

## 🧪 Testing API

Import the following files into Postman.

```
Habit-Tracker-API.postman_collection.json
Habit-Tracker.postman_environment.json
```

Select the environment and test all API endpoints.

---

## ▶️ How to Run

### Backend

```bash
cd backend
node index.js
```

### Frontend

```bash
cd frontend
npm run dev
```

---

## 📸 Output

- Add Habit
- View Habit List
- Delete Habit

---

## 👨‍💻 Author

Developed as a simple Full-Stack Habit Tracker project using React, Express, and SQLite.

---

## 📄 License

This project is for learning and educational purposes.
