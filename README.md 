# Laravel Project with Docker

This project uses Docker to simplify the setup and development process. Follow the steps below to get started.

---

## 🚀 Installation Guide

### 1. Clone the Repository

Make sure your SSH keys are set up for GitLab.

```bash
git clone git@gitlab.com:zitansmail/ctoc.git
cd ctoc
cp .env.example .env
```

### 2. Install PHP Dependencies

```bash
composer install
```

### 3. Start Docker Containers

```bash
docker-compose up -d
```

### 4. Access the Laravel Container

```bash
docker exec -it ctoc_laravel.test_1 bash
```

### 5. Install Node Dependencies and Build Assets

Inside the container:

```bash
npm install
npm run build
```

### 6. Run Migrations

```bash
php artisan migrate
```

---

## ✅ Application is Ready!

You can now access the Laravel application at:

```
http://localhost
```

> ℹ️ Make sure to update your `.env` file for database, mail, and other configurations as needed.
