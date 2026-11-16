# Django hello world

A Django project.

## Tech stack

- Python 3
- Django
- psycopg2 (PostgreSQL)
- Database: SQLite

## Project structure

- `backend2/`: project settings and root URLs
- `polls/`: Django app
- Tests: `polls/tests.py`

## URL routes

Declared in `urls.py`:

- `/blog/`
- `/polls/`

## How to run

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Then open `http://127.0.0.1:8000/`.

---

Author: [Chaouki Bayoudhi](https://github.com/ChaoukiBayoudhi)
