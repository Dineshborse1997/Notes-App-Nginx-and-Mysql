# 🌐 Deploying a Web Application with Nginx and MySQL using Docker

This project demonstrates how to deploy a simple web application using **Nginx** as a web server and **MySQL** as the database, all running in isolated containers using **Docker Compose**.

---

## 📦 Tech Stack

- **Nginx** – Web server and reverse proxy
- **Django** – Server-side scripting language
- **MySQL** – Relational database
- **Docker & Docker Compose** – Container orchestration

## 🖼️ Architecture

![Image Alt](https://github.com/Dineshborse1997/Notes-App-Nginx-and-Mysql/blob/main/Screenshots/diagram-export-7-8-2025-2_56_23-PM.png?raw=true)

## 🚀 Getting Started

### ✅ Install Docker & Docker Compose
```bash
 sudo apt-get install docker.io
 sudo apt-get install docker-compose 
```
### 📥 Clone the Repository

```bash
git clone https://github.com/Dineshborse1997/Notes-App-Nginx-and-Mysql.git
cd Notes-App-Nginx-and-Mysql
```
### ▶️ Start the Application

```bash
docker-compose up --build
```

Visit the app at: [http://Localhost:80]

---

## 📂 Breakdown of Key Files

| File/Folder         | Description                                      |
|---------------------|--------------------------------------------------|
| `mynotes/Dockerfile`| Defines Web app Code                             |
| `nginx/default.conf`| Nginx configuration for routing to PHP container |
| `mysql/init.sql`    | Initializes database with table/data             |
| `docker-compose.yml`| Sets up multi-container application              |

## 🖥️ Screenshot

![Image Alt](https://github.com/Dineshborse1997/Notes-App-Nginx-and-Mysql/blob/main/Screenshots/Screenshot%202025-07-08%20142633.png?raw=true)
![Image Alt](https://github.com/Dineshborse1997/Notes-App-Nginx-and-Mysql/blob/main/Screenshots/Screenshot%202025-07-08%20142319.png?raw=true)
---

## 🎯 Features

- Modular Docker setup using `docker-compose`
- Environment-based DB configuration
- Clean Nginx reverse proxy integration

## 📈 Future Enhancements

- Add GitHub Actions CI/CD pipeline
## 💡 Inspiration

This project is inspired by real-world DevOps workflows and is a great starting point for learning Docker-based deployments.
