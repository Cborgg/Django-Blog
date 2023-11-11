# Django Blogging Website

Welcome to the Django Blogging Website! This is a simple blogging platform built using Django.

## Table of Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Configuration](#configuration)
- [Running the Project](#running-the-project)
- [Usage](#usage)

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed on your machine:

- Python (version 3.x)
- Django (version 4.x)
- Pipenv (for virtual environment management)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/django-blog.git

2. Navigate to the project directory:
  ```bash
   cd django-blogging-website
  ```
3. Installing Django:To install it, make sure you have Python 3.10 or greater installed. Then run
this command from the command prompt:
  ```bash
    python -m pip install .
  ```
### Configuration

1. Create a .env file in the project root and configure the following settings:
```bash

DEBUG=True
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///db.sqlite3
```
Update your_secret_key with a secure Django secret key.

2. Apply database migrations:
```bash
python manage.py migrate
```

### Running the Project

Start the development server:

```bash

python manage.py runserver
```

Visit http://localhost:8000/ in your web browser to access the blogging website.

### Usage

  Create a superuser to manage the admin panel:

  ```bash

python manage.py createsuperuser
```

Access the Django admin panel at http://localhost:8000/admin/ to manage blog posts and users.


