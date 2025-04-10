
# 🚀 Django + MySQL + Nginx – Fully Dockerized 3-Tier App 🐳🌐

Welcome to my latest hands-on project! This repository contains a **Dockerized 3-tier application** featuring Django for the backend, MySQL for data storage, and Nginx as a reverse proxy – all orchestrated using Docker Compose.

---

## 🔧 Project Architecture

```
Client <--> Nginx (Reverse Proxy) <--> Django (App Server) <--> MySQL (Database)
```

### 🔹 Components:

- **Django App Container** – Handles all backend logic and runs on port `8000`
- **MySQL Container** – Manages and stores relational data
- **Nginx Container** – Routes incoming traffic to the Django app seamlessly

---

## ⚙️ Key Features

- 🔗 Custom **Docker Bridge Network** for inter-container communication  
- 💾 **Docker Volumes** for MySQL data persistence  
- 🌐 **Nginx Reverse Proxy** – Access the app via `http://<server-ip>/`  
- 🛠️ Environment variables and **Docker Compose** used for clean orchestration  
- ☁️ **Deployment Ready** – Works great on cloud VMs like **AWS EC2**

---

## 📚 What I Learned

- ✅ Managing **multi-container architecture** using Docker
- ✅ Handling **networking & persistent storage**
- ✅ Setting up **Nginx as a reverse proxy**
- ✅ Deploying full-stack apps on **AWS EC2**

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Start the application**:
   ```bash
   docker-compose up --build
   ```

3. **Access the app**:
   ```
   http://<your-server-ip>/
   ```

---

## 📦 Tech Stack

- **Backend:** Django
- **Database:** MySQL
- **Proxy Server:** Nginx
- **Containerization:** Docker, Docker Compose
- **Deployment:** AWS EC2

---

## 🙌 Final Thoughts

This project strengthened my understanding of Docker, Nginx, networking, and cloud deployment. Feel free to explore, fork, or reach out if you have any questions. Happy coding! 🎯
