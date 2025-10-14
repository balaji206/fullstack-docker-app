# Fullstack Docker App

This project is the initial setup for a **fullstack application** using **Docker and Docker Compose**.  
It provides a clean starting point with separate folders for frontend, backend, and database data.

---

## 📂 Folder Structure

 fullstack-docker-app/
├── backend/
│ └── Dockerfile # Empty backend Dockerfile
│
├── frontend/
│ └── Dockerfile # Empty frontend Dockerfile
│
├── db-data/ # Folder for persistent database data
│
├── .env # Environment variables file (empty for now)
├── docker-compose.yml # Docker Compose file (empty or with version info)
├── README.md # Documentation

## 🛠️ Setup Instructions

1. **Create project folder**
   ```bash
   mkdir fullstack-docker-app
   cd fullstack-docker-app

2. mkdir frontend backend db-data

3. touch docker-compose.yml
   touch backend/Dockerfile
   touch frontend/Dockerfile
   touch .env
   touch README.md

4. git init
   git add .
   git commit -m "Initial project setup with structure and empty files"
