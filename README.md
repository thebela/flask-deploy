# 🚀 Portfolio App – Auto Deployed with Docker & GitHub Actions

This project demonstrates a **real production-style DevOps pipeline** where a Flask application is:

- Containerized with Docker  
- Hosted on AWS Lightsail  
- Automatically deployed on every GitHub push using GitHub Actions  

## 🌍 Live Demo
👉 http://13.234.234.11:30007

## ⚙️ Tech Stack
- Flask (Python backend)
- Docker
- GitHub Actions (CI/CD)
- AWS ec2
- Linux & SSH

## 🔁 How it works
1. Developer pushes code to GitHub  
2. GitHub Actions connects to the Lightsail server via SSH  
3. Latest code is pulled  
4. Docker image is rebuilt  
5. Old container is stopped  
6. New container is started  
7. Website updates automatically  

## 📂 Project Structure
app.py → Flask web app
Dockerfile → Docker image definition
.github/workflows → CI/CD pipeline


## 💼 Why this matters
This setup is exactly how modern startups deploy their backend services.  
It ensures:
- Zero manual deployment  
- Fast updates  
- Reproducible builds  
- Production-grade workflow  

## 👤 About Me
I am **Aman Dinkar**, a Computer Science student with hands-on experience in:
- Docker & Containers  
- AWS & Cloud Hosting  
- CI/CD automation  
- Linux server management  
- Backend deployment workflows

📩 Contact:  
- LinkedIn: https://www.linkedin.com/in/amandinkar37/
- Email: amandinkar67@gmail.com

I help founders and developers **deploy their applications to the cloud**.

📩 Reach out on GitHub or LinkedIn if you need help deploying your app.

