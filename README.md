# FYB Exam - Product Management UI and API's

A full-stack web application built with Laravel (API backend) and Vue.js (SPA frontend).

The app uses Docker for containerized development and SQLite as the database.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/cyrusmanatad/fyb-tech-exam.git

cd fyb-tech-exam
```

### 2. Running the Application (Laravel + Vue.js)

Ensure Docker is installed and running on your machine.

Then initialize the project:

```bash
./init.sh
```

### This script will:

- Build and start the Docker containers
- Install backend and frontend dependencies
- Run migrations
- Compile frontend assets
- Once finished, the application will be available at: `http://localhost:8000`

### Tech Stack

- Backend: Laravel
- Frontend: Vue.js (Vite, Tailwindcss)
- Web Server: NGINX
- Database: SQLite
- Containerization: Docker / Docker Compose
- PHP 8.5