# GreenHabit 🌱

GreenHabit is a Django-based full-stack web application focused on promoting eco-friendly habits and sustainable living. The project includes habit tracking features, user interaction, and media support, built with a clean and modular Django architecture.



## Features

- User authentication
- Eco-friendly habit and goal tracking
- Blog-style posts with likes and comments
- Media file uploads
- Bootstrap-based responsive UI
- Modular Django app structure



## Tech Stack

- Python
- Django
- HTML
- CSS
- JavaScript
- Bootstrap
- SQLite
- Git



## Project Structure

```
greenhabit-django/
│
├── greenhabit-project-main_2/
│   └── greenhabit-project-main/
│       ├── greenhabit/      # Django project settings
│       ├── tracker/         # Habit tracking app
│       ├── media/           # Uploaded files
│       ├── manage.py
│       └── urls.py
│
├── requirements.txt
├── README.md
└── .gitignore
```



## Installation & Setup

### Prerequisites
- Python 3.9 or higher
- pip
- Git

### Steps

1. Clone the repository
```bash
git clone https://github.com/dhruvilad34/greenhabit-django.git
cd greenhabit-django
```

2. Navigate to the Django project directory
```bash
cd greenhabit-project-main_2/greenhabit-project-main
```

3. Create a virtual environment
```bash
python -m venv venv
```

4. Activate the virtual environment

macOS / Linux:
```bash
source venv/bin/activate
```

Windows:
```bash
venv\Scripts\activate
```

5. Install dependencies
```bash
pip install -r ../../requirements.txt
```

6. Apply database migrations
```bash
python manage.py migrate
```

7. Run the development server
```bash
python manage.py runserver
```

8. Open the application in your browser
```
http://127.0.0.1:8000/
```



## Usage

- Register or log in as a user
- Track eco-friendly habits and goals
- Create and interact with posts
- Upload and manage media files




