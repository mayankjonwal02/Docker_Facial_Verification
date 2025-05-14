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


# Clone the repository
git clone https://github.com/mayankjonwal02/Docker_Facial_Verification.git
cd Docker_Facial_Verification

# Build and run the container
docker-compose up --build


## 🏛️ IIT Jodhpur Use Case

This system was developed as a **custom facial verification solution** to digitize and secure **library access** and **resource lending** at **IIT Jodhpur**. It enables **contactless verification** for students and staff using **computer vision** and **AI-based facial recognition**.

---

## 🔒 Security Considerations

- Facial data is processed into **embeddings** (numerical vectors) for enhanced privacy.
- Ensure **HTTPS** is used in production to secure image and data transmission.
- Support for **authentication tokens** (e.g., JWT) can be integrated for authorized API access.

---

## 📌 Future Enhancements

- 🔗 Integration with **Institute ERP** for automated user synchronization  
- 📹 Support for **live video stream recognition**
- 📊 Admin dashboard for managing and viewing **verification logs**
- 📱 Full **mobile app integration** for real-time user verification

