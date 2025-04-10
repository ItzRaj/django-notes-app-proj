
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
