# Backend Setup (Python/Django)

## Prerequisites
- Python 3.9+
- pip (Python package manager)

## Setup Instructions

1. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create Django project:
   ```bash
   django-admin startproject api .
   ```
4. Create starter app (e.g., `core`):
   ```bash
   python manage.py startapp core
   ```
5. Run migrations and start server:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

## Next Steps
- Implement your models, serializers, and API endpoints in the `core` app.
- Configure database settings in `api/settings.py`.
- Add more apps as needed for invoices, users, etc.

---

For help, see the official Django docs: https://docs.djangoproject.com/
