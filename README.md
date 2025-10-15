# 🧩 NodeSQL CRUD Manager

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-8C8C8C?style=for-the-badge&logo=ejs&logoColor=white)
![CRUD](https://img.shields.io/badge/CRUD-Operations-blue?style=for-the-badge)


> 💾 A beginner-friendly full-stack project demonstrating Node.js and MySQL integration with clean CRUD operations and dynamic EJS views.


A full-stack **Node.js + MySQL** CRUD (Create, Read, Update, Delete) web app built with **Express.js**, **EJS**, and **MySQL2**.  
This project demonstrates how Node.js interacts with SQL databases — including routes, forms, and data manipulation — in a clean and minimal user management system.

---

## 🚀 Features

✅ Add new users  
✅ Display all users  
✅ Edit usernames (with password validation)  
✅ Delete users securely  
✅ Generate random users using Faker.js  
✅ UUID for unique user IDs  

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| Backend | Node.js, Express.js |
| Database | MySQL2 |
| Frontend | EJS Templates |
| Utilities | Faker.js, UUID, Method-Override |

---

## 📂 Folder Structure

SQLCLASS/
├── views/
│ ├── add.ejs # Add new user form
│ ├── delete.ejs # Confirm user deletion
│ ├── edit.ejs # Edit username page
│ ├── home.ejs # Homepage showing total users
│ └── show.ejs # Display all users
│
├── index.js # Main Express app
├── package.json
└── package-lock.json


---

## 💡 Learning Highlights

How Node.js communicates with MySQL databases

Using EJS for server-rendered pages

Implementing RESTful routes

Using method-override for PATCH/DELETE support

Structuring full CRUD logic with Express

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/node-sql-crud-manager.git
cd node-sql-crud-manager
```

### 2️⃣ Install dependencies
npm install

### 3️⃣ Create a MySQL Database

Open MySQL and run:

CREATE DATABASE delta_app;

### 4️⃣ Start the server
node index.js

Then visit 👉 http://localhost:8080

## 📸 Screenshots

![Banner](./assets/Banner.png)
![Home Page](./assets/Home%20Page.JPG)
![All Users](./assets/All%20Users.JPG)
![Edit User](./assets/Edit%20User.JPG)
![Delete User](./assets/Delete%20User.JPG)

## 💬 Connect With Me

👨‍💻 [**Mohd Almas**](https://github.com/CodeByAlmas)
🔗 [**LinkedIn**](https://www.linkedin.com/in/mohd-almas-9ab9a6235/)
📧 Email: mohd2almas321@gmail.com

⭐ If you found this useful, please give it a Star on GitHub — it motivates me to keep learning and building!

## 🏷️ Keywords

Node.js · Express · MySQL · CRUD · EJS · Full Stack · Faker.js · UUID