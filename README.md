# Coderr

Django REST API backend for a marketplace-style application.

Built with Django and DRF, including:
- user registration and authentication
- business/customer profiles
- offers
- orders
- reviews
- shared base endpoints

## Quick start

```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Stack

- Python 3.10+
- Django 6.1.1
- Django REST Framework 3.18.1
- SQLite

## Notes

This project is structured as a modular Django backend and follows a test-driven development approach for new features.
