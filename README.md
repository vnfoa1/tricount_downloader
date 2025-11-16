🇫🇷 README — Version Française
<div align="center">
🧩 Tricount_downloader

Exportez vos données Tricount en CSV facilement, via une interface web dans un conteneur Docker.

<img src="https://img.shields.io/badge/Docker-Ready-blue?logo=docker" /> <img src="https://img.shields.io/badge/N8N-Compatible-orange?logo=n8n" /> <img src="https://img.shields.io/badge/WebUI-Minimalist-green" /> <img src="https://img.shields.io/badge/Built%20with-Claude-purple" /> </div>
✨ Présentation

Tricount_downloader est une petite application web qui vous permet de télécharger en un clic les données d’un Tricount au format CSV.
Pensée pour les fans d’automatisation et de self-hosting :

🐳 Installation ultra simple (Docker 1-clic)

🧭 Interface web légère

🌀 Compatible N8N — parfait pour automatiser vos exports

🧱 Fonctionne parfaitement dans Dockge

🔧 Open-source, basé sur le travail de MrNachoX

Développé avec l’aide de Claude, basé sur :
https://github.com/MrNachoX/tricount-downloader

🐳 Installation rapide (Docker)
docker run -d \
  --name tricount_downloader \
  -p 8080:8080 \
  mranachox/tricount-downloader:latest


Ouvrez ensuite :
👉 http://localhost:8080

🧱 Exemple Docker Compose (recommandé)
services:
  tricount_downloader:
    image: mranachox/tricount-downloader:latest
    container_name: tricount_downloader
    ports:
      - "8080:8080"
    restart: unless-stopped

🧭 Comment ça marche ?

Ouvrez l’interface.

Collez l’URL de votre Tricount.

Cliquez sur Download CSV.

(Optionnel) Utilisez cette URL dans une automatisation N8N.

🤝 Crédit & Auteurs

🔧 Basé sur le projet original de MrNachoX

🤖 Amélioré/complété avec Claude

🚀 Packagé et simplifié pour Docker / Dockge
