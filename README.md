# 🌿 AyurSmart — Ayurvedic Clinic Management System

A full-stack clinic management system built as a final year engineering project. Built with Flask, MySQL, and plain HTML/CSS/JS, containerized with Docker and automated with GitHub Actions CI/CD.

---

## 🏗️ Project Structure

\`\`\`
ayursmart/
├── backend1/          # Flask REST API
│   ├── app.py         # Main application
│   ├── requirements.txt
│   └── Dockerfile
├── frontend1/         # Static HTML/CSS/JS
│   ├── index.html
│   ├── dashboard.html
│   └── Dockerfile
├── docker-compose.yml
└── .github/
    └── workflows/
        └── ci.yml
\`\`\`

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python 3.12, Flask, Flask-SQLAlchemy |
| Frontend | HTML, CSS, JavaScript (Nginx) |
| Database | MySQL 8.0 |
| Auth | Session-based, Werkzeug password hashing |
| DevOps | Docker, Docker Compose, GitHub Actions |

---

## 🚀 Run Locally with Docker

### Prerequisites
- Docker Desktop
- WSL2 (Windows)

### Start all services
\`\`\`bash
docker compose up --build
\`\`\`

### Access the app
| Service | URL |
|---|---|
| Frontend | http://localhost:8080 |
| Backend API | http://localhost:5100 |
| MySQL | localhost:3307 |

### Stop all services
\`\`\`bash
docker compose down
\`\`\`

---

## 📦 Modules
- ✅ Patient Management
- ✅ Appointment Booking & Dashboard
- ✅ Prakriti (Dosha) Quiz
- ✅ Health Journal
- ✅ Remedy Recommendations
- ✅ Admin Analytics
- ✅ Billing & Payment (UPI)

---

## 🔄 CI/CD Pipeline

On every push to \`master\`, GitHub Actions:
1. Installs Python dependencies
2. Lints with flake8
3. Builds Docker images
4. Starts all services
5. Health checks backend + frontend
6. Tears down

---

## 👨‍💻 Developer

**Maitri**
