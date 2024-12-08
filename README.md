# TaskFlow

TaskFlow is a simple RESTful API for task management, developed in Flask and using SQLite for data storage. The project is intended for practicing working with APIs, HTTP requests, databases and creating mini-projects.

## Features
- View a list of all tasks.
- Add a new task.
- Update a task (change the name and execution status).
- Delete a task.

## Technologies used
- **Python** (Flask)
- **SQLite** (via SQLAlchemy)
- **Postman** (for testing the API)

## How to run the project
1. Install dependencies:
```bash
pip install flask flask-sqlalchemy

python
from app import app, db
with app.app_context():
    db.create_all()

python app.py
