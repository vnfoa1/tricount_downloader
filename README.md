<p align="center">
  <img src="https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/N8N-Compatible-FE7A16?logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/WebUI-Minimalist-34A853" />
  <img src="https://img.shields.io/badge/Open--Source-Yes-8A2BE2" />
  <img src="https://img.shields.io/badge/Built%20With-Claude-8A2BE2" />
</p>

🧩 Tricount_downloader

Download your Tricount data as CSV via a minimalist Docker-hosted web interface.

<p align="center"> <img src="https://img.shields.io/badge/Docker-Ready-blue?logo=docker" /> <img src="https://img.shields.io/badge/N8N-Compatible-orange?logo=n8n" /> <img src="https://img.shields.io/badge/WebUI-Minimalist-green" /> <img src="https://img.shields.io/badge/Built%20with-Claude-purple" /> </p>
✨ Overview

Tricount_downloader provides a one-click CSV export for all your Tricount data through a tiny, clean web UI.

Perfect for automation lovers and self-hosters:

🐳 Ultra-simple Docker setup

🌐 Minimal web interface

🌀 Works seamlessly with N8N

🧱 Fully compatible with Dockge

🔧 Open-source, based on work by MrNachoX

Source project: https://github.com/MrNachoX/tricount-downloader

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

(Optional) Integrate in an N8N workflow

🤝 Credits

🔧 Original project by MrNachoX

🤖 Extended with the help of Claude

🚀 Packaged for easy Docker / Dockge deployment
