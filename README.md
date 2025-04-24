# Unix-Inspired Task Manager API

A simple **Unix-inspired task manager API** built with **Django** and **Django REST Framework**. This project simulates basic Unix-like task management, where tasks can be created, listed, and updated (similar to Unix processes using `fork`).

## 🚀 Features
- **Create Task** (`POST /api/`) – Fork a new task.
- **List Tasks** (`GET /api/tasks/`) – List all tasks.
- **Get Task Details** (`GET /api/tasks/{id}/`) – Retrieve task by ID.
- **Update Task** (`PUT /api/tasks/{id}/`) – Update task status (e.g., mark as completed).
- **Delete Task** (`DELETE /tasks/{id}/`) – Remove a task.

## ⚙️ Setup Instructions

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- pip (Python package manager)

### Step 1: Clone the Repository

git clone https://github.com/<your-username>/unix-task-manager-api.git
cd unix-task-manager-api


### Step 2: Installl Dependencies
Create a virtual environment:
  python -m venv venv
  source venv/bin/activate  # On Windows use: venv\Scripts\activate

### Step 3: Migrate Database
python manage.py migrate

### Step 4: Run the server
python manage.py runserver

### Tech Stack:
1.Backend: Django, Django REST Framework

2.Database: SQLite (default)

### Testing the API:
You can test the API with tools like Postman or cURL.
