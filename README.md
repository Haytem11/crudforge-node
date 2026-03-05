# Node.js CRUD REST API

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Backend-green?logo=node.js&style=for-the-badge" height="50" />
  <img src="https://img.shields.io/badge/Express.js-Framework-black?logo=express&style=for-the-badge" height="50" />
  <img src="https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb&style=for-the-badge" height="50" />
  <img src="https://img.shields.io/badge/Nodemon-Auto%20Restart-green?logo=nodemon&style=for-the-badge" height="50" />
</p>

A professional RESTful API built with Node.js, Express.js, and MongoDB that demonstrates basic CRUD (Create, Read, Update, Delete) operations using MVC architecture.

---

## 📌 Features

* Create new users
* Fetch all users
* Fetch single user by ID
* Update user details
* Delete user
* Environment variable configuration
* Clean MVC folder structure

---

## 🛠 Tech Stack

Backend

* Node.js
* Express.js

Database

* MongoDB
* Mongoose

Tools

* dotenv
* Nodemon

---

## 📂 Project Structure

node-crud-app

config/
└── db.js

controllers/
└── user.controller.js

models/
└── user.model.js

routes/
└── user.routes.js

.env
.gitignore
server.js
package.json

---

## ⚙️ Installation

### 1 Clone Repository

git clone https://github.com/SRCarlo/crudforge-node.git

### 2 Navigate to Project

cd node-crud-app

### 3 Install Dependencies

npm install

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

Example configuration:

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/procrud

---

## ▶️ Run the Application

Development mode

npm run dev

Production mode

node server.js

Server runs at:

http://localhost:5000

---

## 📡 API Endpoints

Create User
POST /api/users

Get All Users
GET /api/users

Get User by ID
GET /api/users/:id

Update User
PUT /api/users/:id

Delete User
DELETE /api/users/:id

---

## 📥 Example Request Body

{
"name": "Shubham Raut",
"email": "[asphaltshubhuu@gmail.com](asphaltshubhuu@gmail.com)",
"age": 25
}

---

## 🧪 API Testing

You can test the API using tools like:

Postman

---

## 🚀 Future Improvements

* Authentication using JWT
* Input validation
* Pagination
* Role-based access control

---

## 🤝 Contributing

* Contributions are welcome!
* Fork the repository
* Create your feature branch
* Commit your changes
* Push to the branch
* Open a Pull Request

---

## 👨‍💻 Author

**Shubham Raut** – Backend Developer

<p align="center">
  <a href="https://github.com/SRCarlo">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?logo=github&style=for-the-badge" height="40" />
  </a>
  <a href="https://www.linkedin.com/in/shubham-raut-865a21203">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge" height="40" />
  </a>
  <a href="mailto:asphaltshubhuu@gmail.com.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?logo=gmail&style=for-the-badge" height="40" />
  </a>
</p>


---

## 📄 License

This project is licensed for learning and educational purposes.


---

<p align="center">
  <img src="https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&style=for-the-badge" height="50" />
  <img src="https://img.shields.io/badge/GitHub-Repository-black?logo=github&style=for-the-badge" height="50" />
  <img src="https://img.shields.io/badge/Postman-API%20Testing-FF6C37?logo=postman&style=for-the-badge" height="50" />
  <img src="https://img.shields.io/badge/VS%20Code-Editor-007ACC?logo=visual-studio-code&style=for-the-badge" height="50" />
</p>

---
