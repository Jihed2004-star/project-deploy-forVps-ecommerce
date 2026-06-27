# Ecommerce Deploy 🚀

Deployment configuration for the ecommerce fullstack application.

## Stack
- Frontend: React + Vite (Nginx)
- Backend: Express.js
- Database: MongoDB
- Database UI: Mongo Express
- Containerization: Docker + Docker Compose

## Usage

### Prerequisites
- Docker
- Docker Compose

### Run
```bash
git clone https://github.com/Jihed2004-star/ecommerce-deploy.git
cd ecommerce-deploy
docker compose up -d
```

## Services
| Service | Port | Description |
|--|--|--|
| Frontend | 80 | React + Vite |
| Backend | 3000 | Express.js API |
| MongoDB | 27017 | Database |
| Mongo Express | 8081 | Database UI |

## Note
> ⚠️ This repo is for learning purposes only.
> In production, never push `.env` files to GitHub.
