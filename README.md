# WebSite

A small Django site with an English landing page at `/`.

## Setup

Python 3.14 and Django 6.1.

```bash
python -m venv .venv
.venv/bin/pip install "Django==6.1.2"
.venv/bin/python manage.py migrate
.venv/bin/python manage.py runserver
```

Open http://127.0.0.1:8000/

`migrate` creates the local database used by the admin site. The landing page does not need it.

## Layout

- `manage.py` — Django commands
- `webroot/` — settings and root URL configuration
- `pages/` — home page view and template (`pages/templates/pages/home.html`)
