# 🧠 TalkUp Backend – Real-Time Chat Server

This is the backend service for **TalkUp**, a full-stack real-time chat application. It handles user authentication, chat message management, friend requests, password recovery, and real-time messaging using Socket.IO.

## 🚀 Features

- 🔐 User registration and login with hashed passwords
- 💬 Real-time messaging with Socket.IO
- 👫 Friend request system and user connection handling
- 🔑 Password reset via email
- 🌐 RESTful APIs for user and message management
- 🗄️ MongoDB database with Mongoose schema design
- 🛡️ Input validation and error handling

## 📦 Tech Stack

- **Node.js** + **Express.js**
- **MongoDB** + **Mongoose**
- **Socket.IO** – Real-time WebSocket communication
- **JWT** – Authentication
- **Nodemailer** – Password recovery emails
- **BCrypt.js** – Password hashing
- **CORS**, **dotenv**, **Postman**

## 📁 Project Structure

```
talkup-backend/
│
├── config/          # MongoDB & environment setup
├── controllers/     # Business logic for users, chats, auth
├── models/          # Mongoose schemas
├── routes/          # API routes
├── utils/           # Token generation, email utils
├── index.js         # App entry point
├── server.js        # Server initialization
└── .env             # Environment variables
```

## 🧪 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/Meenakshi-Menon/TalkUp-BackEnd-.git
   cd talkup-backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up `.env` with your config:
   ```
   MONGO_URI=your_mongodb_connection
   JWT_SECRET=your_jwt_secret
   EMAIL_USER=your_email
   EMAIL_PASS=your_email_password
   ```

4. Run the server:
   ```bash
   node server.js
   ```

5. API runs at:
   ```
   http://localhost:3000/
   ```

## 📌 Related Repositories

- 👉 [TalkUp Frontend](https://github.com/Meenakshi-Menon/TalkUp-FrontEnd-)
- 📄 [Project Report](../report/TalkUp_Project_Report.pdf)

## 🧑‍💻 Author

Developed by **Meenakshi S Menon**, a final-year CSE (AI/ML) student at VIT Bhopal.

- [LinkedIn](https://www.linkedin.com/in/meenakshi-menon-368211252/)
- [GitHub](https://github.com/Meenakshi-Menon)
