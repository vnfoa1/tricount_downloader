# 🧩 Tricount_downloader

Download your Tricount data as CSV via a minimalist Docker-hosted web interface.

---

## ✨ Overview
One-click CSV export for all your Tricount data through a tiny, clean web UI.

Perfect for automation lovers and self-hosters:  
- 🐳 Ultra-simple Docker setup  
- 🌐 Minimal web interface  
- 🌀 Works seamlessly with N8N  
- 🧱 Fully compatible with Docker  
- 🔧 Open-source, based on work by MrNachoX  

Source project: [GitHub](https://github.com/MrNachoX/tricount-downloader)  

---

## 🐳 Quick Install (Docker)
```bash
docker run -d \
  --name tricount_downloader \
  -p 8080:8080 \
  mranachox/tricount-downloader:latest
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

🚀 Packaged for easy Docker / Docker Compose deployment
