🇬🇧 README — English Version
<div align="center">
🧩 Tricount_downloader

Download your Tricount data as CSV through a clean and simple Docker-hosted web interface.

<img src="https://img.shields.io/badge/Docker-Ready-blue?logo=docker" /> <img src="https://img.shields.io/badge/N8N-Compatible-orange?logo=n8n" /> <img src="https://img.shields.io/badge/WebUI-Minimalist-green" /> <img src="https://img.shields.io/badge/Built%20with-Claude-purple" /> </div>
✨ About

Tricount_downloader lets you extract all your Tricount data as CSV in a single click from a tiny web interface.
Designed for automation lovers and self-hosters:

🐳 Extremely easy Docker setup

🌐 Minimal web UI

🌀 Works with N8N automations

🧱 Fully compatible with Dockge

🔧 Open-source and based on the original work by MrNachoX

Built with the help of Claude, based on:
https://github.com/MrNachoX/tricount-downloader

🐳 Quick Install (Docker)
docker run -d \
  --name tricount_downloader \
  -p 8080:8080 \
  mranachox/tricount-downloader:latest


Open in your browser:
👉 http://localhost:8080

🧱 Docker Compose Example
services:
  tricount_downloader:
    image: mranachox/tricount-downloader:latest
    container_name: tricount_downloader
    ports:
      - "8080:8080"
    restart: unless-stopped

🧭 How It Works

Open the web interface

Paste your Tricount URL

Click Download CSV

(Optional) Use it inside an N8N workflow

🤝 Credits & Authors

🔧 Original base project by MrNachoX

🤖 Extended with the help of Claude

🚀 Packaged for Docker / Dockge deployment
