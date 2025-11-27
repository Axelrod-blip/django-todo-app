# Django TODO App

A simple TODO application built with Django.

## Features

- Create, Read, Update, and Delete (CRUD) TODOs
- Mark TODOs as resolved
- Set due dates for tasks

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Axelrod-blip/django-todo-app.git
    cd django-todo-app
    ```

2.  **Create a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    # Windows
    .\venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies:**

    ```bash
    pip install django
    ```

4.  **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

## Usage

1.  **Run the development server:**

    ```bash
    python manage.py runserver
    ```

2.  **Open your browser:**
    Navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Running Tests

To run the automated tests:

```bash
python manage.py test
```
