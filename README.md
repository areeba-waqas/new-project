# DevOps Portfolio Website 🚀

## 🌐 Live Demo
https://new-project-production.up.railway.app

## 📌 Overview

This project is a containerized portfolio website built as part of my DevOps learning journey. It demonstrates the use of Docker, Git, and CI/CD practices in a Linux-based development environment.

---

## 🛠️ Tech Stack

* Linux (WSL Ubuntu)
* Git & GitHub
* Docker
* Nginx

---

## 📦 Docker Setup

### Build the image

```bash
docker build -t new-project .
```

### Run the container

```bash
docker run -d -p 8080:80 new-project
```

Access the app:
http://localhost:8080

---

## ⚙️ CI/CD Pipeline

This project includes a basic CI pipeline using GitHub Actions.

* Automatically builds Docker image on every push to `main`
* Ensures code integrity and consistency

---

## 📁 Project Structure

* `index.html` → main webpage
* `style.css` → styling
* `Dockerfile` → container configuration

---

## 🎯 Learning Outcomes

* Hands-on experience with Docker containerization
* Working with Git and GitHub workflows
* Setting up basic CI/CD pipeline
* Linux-based development using WSL

---

## 🚀 Future Improvements

* Deploy on AWS EC2
* Add Kubernetes support
* Implement monitoring/logging

---

## 👩‍💻 Author

Areeba Waqas
