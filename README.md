# SmartClass — Django Based Smart Classroom Management System

SmartClass is a web-based classroom management platform built using **Python and Django**.  
The system helps teachers and students interact digitally by providing tools for classroom communication, discussions, and learning management.

The goal of SmartClass is to improve classroom engagement through a centralized digital platform.

---

## Features

- **Teacher & Student Authentication** — Secure login system for users.
- **Classroom Interaction** — Enables communication between teachers and students.
- **Discussion Management** — Organized discussion and question system.
- **Web-Based Learning Environment** — Accessible through a browser from any device.
- **Database Integration** — Persistent data storage using Django database.

---

## Tech Stack

| Layer | Technology |
|------|-----------|
| Backend | Python, Django |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite |
| Framework | Django |

---

## Project Structure

```
Django_SmartClassProject
│
├── manage.py
├── Django_SmartClassProject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── templates/
├── static/
└── db.sqlite3
```

---

## Getting Started

### Prerequisites

Before running the project, ensure the following are installed:

- Python 3.8+
- pip package manager

---

## Installation

### Clone the Repository

```
git clone https://github.com/DurgaSwaroopa2005/Django_SmartClassProject.git
```

### Navigate to the Project Directory

```
cd Django_SmartClassProject
```

### Install Dependencies

```
pip install -r requirements.txt
```

### Apply Database Migrations

```
python manage.py migrate
```

### Run the Development Server

```
python manage.py runserver
```

Now open the browser and go to:

```
http://127.0.0.1:8000/
```

---

## How It Works

1. Users register or log in to the system.
2. Teachers manage classroom discussions and activities.
3. Students participate in discussions and interact with the platform.
4. All data is stored using Django’s database system.

---

## Contributors

- [Durga Swaroopa](https://github.com/DurgaSwaroopa2005)  
- [Shaik Mubeena](https://github.com/YOUR_GITHUB_USERNAME)

---

## License

This project was developed for educational and academic purposes.
