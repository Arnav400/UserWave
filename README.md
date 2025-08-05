# UserWave

A lightweight, backend-only RESTful API for managing user data, built with **Node.js** and **Express.js**.  
This project simulates an internal tool for performing CRUD operations using mock JSON data as a database substitute.

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **JavaScript**
- **Postman** (for API testing)

---

## 📌 Use Case

UserWave acts as a mock backend for an internal admin system or user service where simple CRUD operations are needed — ideal for testing, prototyping, or demonstrating backend fundamentals.

---

## 🚀 Features

- RESTful API design
- Full CRUD support: Create, Read, Update, Delete users
- Dynamic route parameter handling (`/api/users/:id`)
- Simple middleware for parsing form data
- Mock data stored in a static JSON file
- Clean error messages and HTTP response codes

---

## 📂 Folder Structure

UserWave/
├── index.js # Main Express server
├── MOCK_DATA.json # Static mock database
├── package.json
└── task.txt # Notes (optional)



---

## 📡 API Endpoints

| Method | Route              | Description            |
|--------|--------------------|------------------------|
| GET    | `/api/users`       | Get all users          |
| GET    | `/api/users/:id`   | Get user by ID         |
| POST   | `/api/users`       | Add new user           |
| PATCH  | `/api/users/:id`   | Update user by ID      |
| DELETE | `/api/users/:id`   | Delete user by ID      |

🧪 **Sample HTML route**:  
Visit `/users` in your browser to view a basic HTML-rendered list of user names.

---

## 🧪 How to Test (Locally)

1. **Clone the repo**
```bash
git clone https://github.com/Arnav400/UserWave.git
cd UserWave
cd UserWave

Install dependencies

bash
Copy
Edit
npm install
Start the server

bash
Copy
Edit
node index.js
Open in browser or Postman

http://localhost:8000/api/users

Use Postman to test GET, POST, PATCH, and DELETE operations.

✅ Example User Object (from MOCK_DATA.json)
json
Copy
Edit
{
  "id": 1,
  "first_name": "John",
  "last_name": "Doe",
  "email": "john.doe@example.com"
}
📃 License
This project is open-source and licensed under the MIT License.
