# Mental Health Chatbot Backend

A robust and secure Node.js/Express backend for a Mental Health Support Platform. It enables user authentication, real-time chat management, doctor-patient connections, and appointment scheduling.

## ✨ Features

- User registration and login with JWT authentication
- Role-based access control (Patient, Doctor, Admin)
- Real-time chat functionality with conversation history
- Doctor availability and appointment booking system
- Secure API endpoints with input validation
- PostgreSQL database integration

## 🛠️ Tech Stack

- **Runtime**: Node.js + Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT + bcryptjs
- **Others**: dotenv, CORS, Helmet, Morgan, Sequelize/Prisma

## 📁 Project Structure

```bash
my-project-backend/
├── src/
│   ├── config/          # Database configuration
│   ├── controllers/     # Business logic
│   ├── routes/          # API route definitions
│   ├── models/          # Database models
│   ├── middleware/      # Authentication & validation
│   └── utils/           # Helper functions
├── .env.example
├── package.json
├── server.js
└── README.md
