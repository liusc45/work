# 🚀 WordPress + Caddy + Docker

This repo contains a minimal and production-ready setup for running **WordPress** behind **Caddy** using **Docker Compose**.

## 📦 Includes

- 🐳 WordPress (PHP-FPM)
- ⚡ Caddy (HTTP/3, TLS, Brotli, security headers)
- 🔐 Auto HTTPS via Let's Encrypt
- 📁 Persistent volume for data

## 🚀 Quick Start

```bash
# (Optional) Install Docker (for testing)
curl -fsSL https://test.docker.com -o test-docker.sh && sudo sh test-docker.sh

# Clone this repo
g[it clone https://github.com/youruser/yourrepo.git](https://github.com/liusc45/work.git)
cd  work	

# Launch the stack
docker compose up -d
