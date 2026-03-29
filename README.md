# Parking-Pro: Distributed Infrastructure Solution

## 📝 System Architecture
An integrated parking management ecosystem utilizing a multi-service approach. 

### 📦 Components
- **Primary API:** Django REST Framework (Python)
- **High-Concurrency Service:** Go (Golang)
- **Frontend Interface:** Next.js / Tailwind CSS
- **Persistence:** PostgreSQL via Docker-Compose

## 🚀 Execution Guide
1. Initialize PostgreSQL: `docker-compose up -d`
2. Run Django: `python manage.py runserver 8001`
3. Run Go Service: `go run main.go`
4. Start Web Client: `npm run dev`