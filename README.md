🎵 Spotify Playlist Maker

A web application that allows users to create and manage Spotify playlists seamlessly.
This project is built using JavaScript, HTML, CSS, and packaged with Vite for the frontend, with a Node.js backend.
It also includes Docker support, Kubernetes manifests, and a Jenkinsfile for CI/CD automation.

🚀 Features

🔑 Spotify API Integration – Authenticate and connect with Spotify.

🎶 Playlist Creation – Create new playlists directly from the app.

➕ Add Tracks – Search and add songs to your playlists.

📱 Responsive UI – Built with a modern frontend stack (Vite + JS + CSS).

🐳 Dockerized Setup – Run both frontend and backend in containers.

☸️ Kubernetes (k8s) Manifests – Deploy easily on Kubernetes clusters.

⚡ CI/CD Pipeline – Automated build and deploy using Jenkins.

🛠️ Tech Stack

Frontend: Vite, JavaScript, CSS, HTML

Backend: Node.js (Express)

Containerization: Docker, Docker Compose

Deployment: Kubernetes (k8s)

CI/CD: Jenkins

Package Management: npm
```bash
📂 Project Structure
Spotify-Playlist-Maker/
│── backend/           # Backend code (Node.js + Express)
│── frontend/          # Frontend code (Vite + JS + CSS)
│── k8s/               # Kubernetes manifests
│── public/            # Static files
│── src/               # Source files for frontend
│── Dockerfile         # Docker configuration (frontend/backend)
│── docker-compose.yaml # Docker Compose setup
│── Jenkinsfile        # CI/CD pipeline configuration
│── package.json       # Dependencies and scripts
│── vite.config.js     # Vite configuration
```
⚙️ Installation & Setup
🔹 Clone the Repository
```bash
git clone https://github.com/Harsh202004/Spotify-Playlist-Maker.git
cd Spotify-Playlist-Maker
```
🔹 Install Dependencies
```bash
npm install
```
🔹 Run Locally (Frontend + Backend)

Frontend:
```bash
cd frontend
npm run dev
```

Backend:
```bash
cd backend
npm start
```
🐳 Run with Docker
```bash
Build and start containers:

docker-compose up --build
```
☸️ Deploy with Kubernetes

Apply manifests:
```bash
kubectl apply -f k8s/
```
🔄 CI/CD with Jenkins

This repo contains a Jenkinsfile that automates:

Build

Test

Docker image creation

Deployment to Kubernetes
