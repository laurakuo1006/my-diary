# Simple Diary Website

## Overview
This is a simple diary website that allows users to add, delete, update, and read diary entries. You can create an account and easily manage your diary entries through the web interface.

## Getting Started

### Prerequisites
- Python 3.x
- Virtual Environment (recommended)

### Installation Steps

1. **Clone this repository**
   ```sh
   git clone https://github.com/laurakuo1006/my-diary.git
   cd my-diary
   ```

2. **Activate Virtual Environment**
   ```sh
   source .venv/bin/activate
   ```

3. **Create a Superuser**
   To access the admin interface for managing diary entries, create a superuser:
   ```sh
   python manage.py createsuperuser
   ```
   You will be prompted to provide a username and password, which will be used to log in later.

4. **Run the Server**
   Start the Django development server:
   ```sh
   python manage.py runserver
   ```

### Accessing the Website
Once the server is running, you can access the diary website in your browser at:
```
http://127.0.0.1:8000/
```

Log in using the credentials you created with `createsuperuser` to start adding, deleting, updating, and reading your diary entries.
