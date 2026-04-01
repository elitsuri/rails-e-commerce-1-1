# rails-e-commerce-1

> Rails E-Commerce 1: E-commerce store with Rails, Stripe, PostgreSQL, and Active Storage

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Ruby, Rails, PostgreSQL, Redis, Sidekiq

## 🏗️ Architecture
Three-tier architecture: Ruby, Rails backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/rails-e-commerce-1
cd rails-e-commerce-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
