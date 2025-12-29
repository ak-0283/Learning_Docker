# 🐳 Learning Docker with CampusX

This repository tracks my Docker learning journey following the CampusX YouTube series.

- 🎥 Source: CampusX Docker playlist on YouTube
- 🎯 Goal: Build a practical understanding of Docker fundamentals and workflows

## 🛠️ What I'm Using
- 🧩 Docker Desktop on Windows
- 💻 Windows PowerShell (`powershell.exe`)

## 🗂️ Folder Structure
- `docker_learning_pdf/`: 📚 Reference PDFs and notes

## 📈 Progress So Far
- ✅ 📄 Dockerfile basics: `FROM`, `WORKDIR`, `COPY`, `RUN`, `EXPOSE`, `CMD` (see `1stpart.txt`)
- ✅ 🏗️ Build images: `docker build -t <user>/<name> .` (see `2ndpart.txt`)
- ✅ 🚀 Run containers with port mapping: `docker run -p 8000:8501 <user>/<name>` (see `2ndpart.txt`)
- ✅ ☁️ Push to Docker Hub: `docker login` + `docker push <user>/<name>` (see `3rdpart.txt`)
- ✅ ⬇️ Pull and run images from Docker Hub: `docker pull <user>/<name>` + `docker run` (see `4thpart.txt`)

## ✅ Topics Covered / Plan
- Basics: images, containers, layers
- Working with `docker run`, `docker ps`, `docker logs`
- Building images with `Dockerfile`
- Volumes and bind mounts
- Networking: ports, bridge networks
- Multi-stage builds
- Pushing/pulling from Docker Hub

## ▶️ Quick Start
Ensure Docker Desktop is running, then try:

```
powershell
docker --version
docker run hello-world
```

## 🔗 Useful Links
- CampusX on YouTube: https://www.youtube.com/@campusx-official
- Docker Docs: https://docs.docker.com/

## 🚀 First Project
- 🧪 GitHub (Dockerized app): https://github.com/ak-0283/Crop-Recommendation-System
- 🐳 Docker Hub image: https://hub.docker.com/r/abhay0283/crop