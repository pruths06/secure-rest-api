# Secure REST API with JWT & Role-Based Access

## 📌 Overview
A RESTful API built using Flask and PostgreSQL with JWT authentication and role-based access control (RBAC).

## 🔧 Tech Stack
- Flask
- PostgreSQL
- SQLAlchemy
- JWT (PyJWT)
- Docker

## 🚀 Features
- User registration & login
- JWT-based authentication
- Role-based access (admin, user)
- Swagger/OpenAPI documentation

## 🗂️ Project Structure
project-root/
├── app/
│   ├── __init__.py
│   ├── models.py
│   ├── routes.py
│   └── auth.py
├── config.py
├── requirements.txt
├── run.py
└── Dockerfile

## 🧪 Running Locally
```bash
docker build -t secure-api .
docker run -p 5000:5000 secure-api
