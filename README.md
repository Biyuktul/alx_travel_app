# alx_travel_app

## Milestone 1: Setup and Database Configuration

This milestone establishes the foundation of the **alx_travel_app** Django backend for a travel listing platform.

---

### Project Overview

This repository covers the initial setup of a scalable Django project with MySQL database integration, REST API structure, automated API documentation using Swagger, and essential developer tools and configurations.

---

### Key Features

- Django project named `alx_travel_app` with a core app `listings`
- MySQL database configuration using environment variables (`django-environ`)
- REST API setup with Django REST Framework
- CORS handling via `django-cors-headers`
- Automated Swagger API docs at `/swagger/` with `drf-yasg`
- Dependency and environment management for reliable teamwork
- Version control initialized with Git

---

### Requirements

- Python, Django, Django REST Framework
- MySQL
- `django-environ`, `django-cors-headers`, `drf-yasg`
- Celery & RabbitMQ (for future use)

---

### Getting Started

1. Clone the repository and navigate to the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Copy `.env.example` to `.env` and update with your MySQL credentials.
4. Apply migrations:
   ```bash
   python manage.py migrate
   ```
5. Start the development server:
   ```bash
   python manage.py runserver
   ```
6. Use Postman to test endpoints.
7. API docs are available at [http://localhost:8000/swagger/](http://localhost:8000/swagger/).

---

### Structure

- `alx_travel_app/` - Django project root
  - `listings/` - Core app
  - `settings.py` - Configuration
  - `urls.py` - Routing and Swagger docs
- `requirements.txt` - Dependencies

---

**Repository initialized and maintained according to ALX guidelines.**