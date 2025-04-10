# Django Real-Time Chat Application

![Build](https://img.shields.io/badge/build-passing-brightgreen)![Coverage](https://img.shields.io/badge/coverage-96%25-yellowgreen)
![PyPI](https://img.shields.io/badge/pypi-v1.0.0-blue)![Code Style](https://img.shields.io/badge/code%20style-pep8-green)![Database](https://img.shields.io/badge/database-PostgreSQL-blue)![WebSockets](https://img.shields.io/badge/websockets-enabled-orange)![Framework](https://img.shields.io/badge/framework-Django-green)![Downloads](https://img.shields.io/badge/downloads-1.2M%2Fmonth-brightgreen)![Downloads](https://img.shields.io/badge/downloads-1.2M%2Fmonth-brightgreen)[![Demo](https://img.shields.io/badge/demo-Live%20Chat%20App-red?logo=django)](#)

---

This is a real-time chat application built with Django, Django Channels, WebSockets, and PostgreSQL. The application allows users to join chat rooms, send real-time messages, and interact with other users.


![Project Image](images/Screenshot%202025-04-10%20235603.png)

---

## Features

- **Real-Time Messaging**: Powered by Django Channels and WebSockets.
- **Chat Rooms**: Users can join specific chat rooms.
- **Message Persistence**: Messages are stored in a PostgreSQL database.
- **Like Functionality**: Users can like messages.
- **Debugging Tools**: Integrated `django-debug-toolbar` for development.

---

## Prerequisites

Before setting up the project, ensure you have the following installed:

- Python 3.8 or higher
- PostgreSQL
- Redis (for WebSocket channel layers)
- Git

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
cd chat_appliction
```

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### 4. Configure the `.env` File

Create a `.env` file in the root directory and add the following environment variables:

```
SECRET_KEY=your-secret-key
DEBUG=True
Name=your-database-name
user=your-database-username
Password=your-database-password
host=localhost
port=5432
```

### 5. Set Up the Database

Run the following commands to apply migrations and set up the database:

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Collect Static Files

Run the following command to collect static files:

```bash
python manage.py collectstatic
```

```

---

Would you like me to save this updated file and send it back to you?
```
