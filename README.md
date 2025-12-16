# GreenHabit 🌱

GreenHabit is a Django-based web application focused on encouraging eco-friendly habits and sustainable living. The project is built using Django for the backend and standard web technologies for the frontend, with an emphasis on clean structure and ease of use.



## Features

- Clean and simple interface
- Django-based backend architecture
- Modular and maintainable code structure
- Sustainability-focused application concept
- Easy to extend with additional features



## Tech Stack

- Python
- Django
- HTML
- CSS
- JavaScript
- SQLite
- Git



## Project Structure

```
greenhabit-django/
├── manage.py
├── greenhabit/
├── app/
├── templates/
├── static/
├── db.sqlite3
└── requirements.txt
```



## Installation & Setup

### Prerequisites
- Python 3.9 or higher
- pip
- Git

### Steps

1. Clone the repository
```bash
git clone https://github.com/your-username/greenhabit-django.git
cd greenhabit-django
```

2. Create a virtual environment
```bash
python -m venv venv
```

3. Activate the virtual environment

macOS / Linux:
```bash
source venv/bin/activate
```

Windows:
```bash
venv\Scripts\activate
```

4. Install dependencies
```bash
pip install -r requirements.txt
```

5. Run database migrations
```bash
python manage.py migrate
```

6. Start the development server
```bash
python manage.py runserver
```

7. Open the application in your browser
```
http://127.0.0.1:8000/
```



## Usage

- Run the application locally
- Navigate through the web interface
- Modify or extend features using Django views and templates



