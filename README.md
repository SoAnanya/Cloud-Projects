Dockerized Node.js + MongoDB App

This project is a simple Node.js Express application connected to a MongoDB database, fully Dockerized with Docker Compose support.

Features

Express.js API for basic CRUD operations for users.

MongoDB database to store user data.

Dockerized for easy deployment.

Docker Compose configuration to run app and database together.

Project Structure

.
├── server.js
├── package.json
├── Dockerfile
├── mongodb.yml (or docker-compose.yml)
├── public/ (static files)
└── README.md

How to Run

**1. Clone the repository**

git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

**2. Build the Docker image**

docker build -t testapp:1.0 .

**3. Run with Docker**

docker run -p 5050:5050 testapp:1.0

**Or use Docker Compose:**

docker compose -f mongodb.yml up -d

**API Endpoints**

GET /getUsers — Fetch all users
POST /addUser — Add a new user

**Tech Stack**

Node.js
Express.js
MongoDB
Docker & Docker Compose

**License**

MIT — Free to use for learning and personal projects.

