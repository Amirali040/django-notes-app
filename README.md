# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

# 🚀 Django Notes App - DevOps Deployment on AWS

A Dockerized Django Notes Application deployed on AWS EC2, supporting both local and cloud environments.


## 📌 Project Description

This project demonstrates a *containerized Django Notes Application* built using Docker and deployed on AWS EC2.  

It ensures:
- Consistent environment across local and cloud  
- Easy deployment using Docker  
- Accessibility via browser using localhost and public IP  

> ⚡ Showcases real-world DevOps workflow including containerization and cloud deployment.


### 🔷 AWS EC2 Server (Production)
Application running on AWS EC2 with Docker container logs:

![WhatsApp Image 2026-04-07 at 7 07 09 AM (1)](https://github.com/user-attachments/assets/26bfa017-eeeb-4d31-ac3d-416420cee5b2)


### 🔷 Local Development (Docker - Port 8000)
Application running locally using Docker:

http://localhost:8000

![WhatsApp Image 2026-04-07 at 7 07 09 AM](https://github.com/user-attachments/assets/0cfb2671-3c8a-4daf-b8ff-c20fa031120a)


## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
