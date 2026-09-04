# 🚀 DevOps Docker Project

A simple DevOps project demonstrating how to build and deploy a custom Nginx web application using Docker on AWS EC2.

## 🛠️ Technologies Used

- AWS EC2
- Docker
- Nginx
- Linux
- Git
- GitHub
- HTML

## 🏗️ Architecture

GitHub → Docker Image → Docker Container → Nginx → AWS EC2 → Web Browser

## 🚀 How It Works

1. AWS EC2 hosts the application.
2. Docker runs the Nginx container.
3. A custom `index.html` page is copied into the Nginx image.
4. EC2 port `8080` maps to container port `80`.
5. The application is accessible through the EC2 public IP.

## 🐳 Docker Commands

Build the image:

```bash
docker build -t devops-nginx:v1 .
