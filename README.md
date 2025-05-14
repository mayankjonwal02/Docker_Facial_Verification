# 🧠 Facial Verification System – Django Backend (Dockerized)  
**Library, IIT Jodhpur**

This project is a **facial verification backend system** developed using **Django**, designed specifically for the **Library of IIT Jodhpur** to enable seamless, secure, and automated user verification using facial recognition technology. The application is fully **Dockerized** for easy deployment and scalability.

---

## 🚀 Features

- 🔐 Facial verification and authentication API
- 🧾 User registration & facial data storage
- 📷 Face matching using embeddings
- 📦 Dockerized for hassle-free setup and deployment
- 🏫 Built specifically for IIT Jodhpur’s library use-case

---

## 🛠️ Tech Stack

- **Backend Framework:** Django (Python)
- **Face Recognition:** `face_recognition` (dlib)
- **Containerization:** Docker
- **Database:** PostgreSQL / SQLite (configurable)
- **Web Server:** Gunicorn + Nginx (optional in production)

---
---

## ⚙️ Setup Instructions

### 🚧 Prerequisites

- Docker & Docker Compose
- Python 3.8+ (for local development)

### 🐳 Docker Deployment

```bash
# Clone the repository
git clone https://github.com/mayankjonwal02/Docker_Facial_Verification.git
cd Docker_Facial_Verification

# Build and run the container
docker-compose up --build
