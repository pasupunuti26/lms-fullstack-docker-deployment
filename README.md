🚀 LMS Fullstack Deployment with Docker & AWS

📌 Overview

This project is a fullstack Learning Management System (LMS) deployed on AWS EC2 using Docker and Docker Compose.

It includes frontend, backend, and PostgreSQL database with persistent storage.

---

🧱 Architecture

Frontend (Nginx)
↓
Backend (Node.js + Prisma)
↓
PostgreSQL (Docker Volume for persistence)

---

⚙️ Tech Stack

- Frontend: React
- Backend: Node.js
- Database: PostgreSQL
- ORM: Prisma
- DevOps: Docker, Docker Compose
- Deployment: AWS EC2

---

🔥 Key Features

- Fullstack LMS application
- REST API integration
- Dockerized services (frontend, backend, database)
- Persistent database using Docker volumes
- Production deployment on AWS EC2

---

🐳 Docker Setup

Start application

docker-compose up -d

Stop application

docker-compose down

---

💾 Database Persistence

- PostgreSQL uses Docker volumes
- Data remains safe after container restart
- Avoid using:
  docker-compose down -v (this deletes data)

---

🧪 Testing

- Restarted containers → data persisted
- Verified API endpoints
- Verified UI + backend integration

---

🌐 Live Demo

http://<your-ec2-ip>

---

📸 Screenshots

(Add your screenshots here)

---

🧠 Key Learnings

- Docker networking and service communication
- Database persistence using volumes
- Debugging container crashes
- Prisma integration with PostgreSQL
- Real-world deployment on AWS EC2

---

👨‍💻 Author

Harish Pasupunuti
