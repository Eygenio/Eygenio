# 👋 Hi, I'm Evgeny — Python Backend Developer

Python backend developer focused on building clean, maintainable REST APIs.  
I design applications with layered architecture, write unit/integration/e2e tests, and ship them in Docker.

---

## 🛠️ Technologies

- **Backend:** Python 3.10+, FastAPI, Django, Django REST Framework  
- **Databases:** PostgreSQL, SQLite, SQLAlchemy 2.0 (async), Alembic  
- **Async & Background Jobs:** Celery, RabbitMQ  
- **Infrastructure:** Docker, docker-compose, Nginx, Gunicorn, Uvicorn  
- **Testing:** Pytest, pytest-asyncio, pytest-cov, Faker, TestClient (sync & async)  
- **Code Quality:** mypy, ruff, flake8, black, isort, pre-commit  
- **Other:** Pydantic, Poetry, uv, colorlog, Git, Linux 

---

## 🚀 Featured Projects

### 🐦 Twitter Clone API
Backend for a Twitter-like social network: users, tweets, likes, follows, media uploads, background tasks.
**Stack:** FastAPI, PostgreSQL, SQLAlchemy 2.0 (async), Celery, RabbitMQ, Docker, Nginx, Poetry, Pytest, Ruff, MyPy
**Highlights:**
•	REST API with interactive docs (Swagger / ReDoc)
•	API‑key authentication via custom header and FastAPI dependencies
•	Async PostgreSQL access (asyncpg + SQLAlchemy 2.0)
•	Clean Architecture with Repository and Unit of Work patterns
•	Follow/unfollow with user existence checks
•	Likes with permission checks (no duplicate likes, cannot remove others’ likes)
•	Media upload and deletion
•	Celery background tasks with RabbitMQ broker
•	Centralized error handling and request‑ID middleware
•	Full Docker setup (app, worker, PostgreSQL, RabbitMQ, Nginx)
•	Comprehensive test suite: unit, integration, e2e
•	Code quality: ruff, mypy, pre-commit
•	Structured logging with colorlog

🔗 https://github.com/Eygenio/Twitter_Clone_API

---

### 🛒 Megano Store API
Backend for an online store (product catalog, shopping cart, orders, payments, users).

**Stack:** Django 6, DRF, PostgreSQL, Docker, Nginx, Gunicorn, WhiteNoise, uv, pytest, mypy, flake8 
**Highlights:**
•	REST API with Clean Architecture (domain, application, infrastructure, interfaces, DTOs)
•	User authentication, profile & avatar management
•	Product catalog with categories, tags, filtering, sorting, pagination
•	Session- and DB-backed shopping cart
•	Order creation with delivery cost calculation and payment simulation
•	Django admin panel
•	Full Docker environment (Nginx + Gunicorn + PostgreSQL)
•	Test suite: unit, integration, e2e
•	Code quality: black, isort, flake8, mypy
•	Structured logging with colorlog

🔗 https://github.com/Eygenio/Megano_Store_API

---

## 📌 In Progress  
Other repositories will be updated and added after refactoring.
