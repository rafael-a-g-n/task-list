# 📝 Laravel Task List

🚀 [Live Demo](https://task-list-ieo6.onrender.com)

<p align="center">
	<img src="https://img.shields.io/badge/Laravel-8.3-red?logo=laravel" alt="Laravel">
	<img src="https://img.shields.io/badge/PHP-8.3-blue?logo=php">
	<img src="https://img.shields.io/badge/MySQL-Database-yellow?logo=mysql">
	<img src="https://img.shields.io/badge/Docker-Ready-blue?logo=docker">
	<img src="https://img.shields.io/badge/Composer-Dependency-green?logo=composer">
</p>

## ✨ Overview

Laravel Task List is a simple yet robust web application for managing your daily tasks. Built with the power of Laravel, it demonstrates modern PHP development, clean architecture, and a smooth user experience.

## 🌟 Features

- 📝 Create, view, edit, and delete tasks
- ✅ Toggle task completion status
- 📄 Paginated task list
- 🛡️ Form validation for all task fields
- 🩺 Health check endpoint for database
- 🎨 Clean Blade UI templates

## 🛠️ Skills & Technologies Leveraged

- **Laravel** (Routing, Eloquent ORM, Blade, Validation)
- **PHP 8.3**
- **Composer**
- **MySQL** (or compatible DB)
- **Docker** (for containerized dev)
- **HTML5 & CSS3**
- **MVC Architecture**
- **RESTful Principles**

## 🚦 Quick Start

```bash
git clone https://github.com/rafael-a-g-n/task-list.git
cd task-list
composer install
cp .env.example .env
# Edit .env for your DB credentials
php artisan key:generate
php artisan migrate
php artisan serve
```

Visit [http://localhost:8000](http://localhost:8000) in your browser.

## 🔗 Main Endpoints

- `/tasks` — List all tasks (paginated)
- `/tasks/create` — Create a new task
- `/tasks/{task}` — View a single task
- `/tasks/{task}/edit` — Edit a task
- `/tasks/{task}` (PUT) — Update a task
- `/tasks/{task}` (DELETE) — Delete a task
- `/tasks/{task}/toggle-complete` (PUT) — Toggle completion status
- `/health-db` — Database health check

## 🗂️ Model Structure

**Task**
- `title` (string)
- `description` (string)
- `long_description` (string)
- `completed` (boolean)

## 🧩 Dev Container & Codespaces

This project includes a Dockerfile for consistent PHP/Laravel setup. For GitHub Codespaces or VS Code Dev Containers, add a `.devcontainer/devcontainer.json` referencing the Dockerfile for automatic environment setup.

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.