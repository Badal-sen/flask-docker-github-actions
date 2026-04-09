# 🚀 Dockerized Flask App with GitHub Actions CI

This project demonstrates a Flask application containerized with Docker and automated using GitHub Actions.

---

## 📌 Project Overview

- Flask app running inside Docker
- CI pipeline using GitHub Actions
- Automatic build, run, and test

---

## 🛠️ Tech Stack

- Python
- Flask
- Docker
- GitHub Actions

---

## ⚙️ CI Workflow

The pipeline performs:

1. Checkout code
2. Build Docker image
3. Run container
4. Test app using curl

---

## 🐳 Run Locally

```bash
docker build -t flask-docker-github-actions .
docker run -p 5001:5000 flask-docker-github-actions

## Minor Update
Testing pull request workflow for profile achievement.
    
