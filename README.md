# Library Management System

A starter web-based Library Management System built with Python, Django, and SQLite.

## Features
- Admin login and management through Django Admin
- Add and manage books
- Register library members
- Issue books to members
- Record book returns
- Track due dates and issue status

## Requirements
- Python 3.10+
- pip

## Run locally
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open http://127.0.0.1:8000/ for the application.
Open http://127.0.0.1:8000/admin/ to manage records.

## Notes
- This project uses SQLite by default, so no separate database server is needed.
- This is an educational starter project. Before real deployment, configure production settings,
  secure credentials, add tests, and review access controls.
