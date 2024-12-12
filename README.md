# Django Project - Little Lemon (Coursera)

This repository contains the codebase for the **Little Lemon** project, a sample Django web application for managing restaurant-related operations. The project demonstrates the use of Django's core features, database integration, and app modularity.

## Features
- **Modular Design**: Separation of concerns through Django apps.
- **Database Integration**: SQLite used as the backend database.
- **Scalability**: Easily extendable for additional functionalities.

## Project Structure
```
Django/
├── littlelemon/       # Main project folder
│   ├── __init__.py    # Project initialization
│   ├── settings.py    # Configuration settings
│   ├── urls.py        # URL routing
│   └── wsgi.py        # WSGI application
├── restaurant/        # Restaurant app folder
│   ├── migrations/    # Database migrations
│   ├── __init__.py    # App initialization
│   ├── admin.py       # Admin configurations
│   ├── apps.py        # App configurations
│   ├── models.py      # Data models
│   ├── tests.py       # Unit tests
│   └── views.py       # View functions
├── db.sqlite3         # SQLite database file
├── manage.py          # Django CLI utility
```

## Prerequisites
- Python 3.8+
- Django 4.0+

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/chandrachhetri/Django.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Django
   ```

3. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows, use `env\Scripts\activate`
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Apply migrations:
   ```bash
   python manage.py migrate
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage
- Access the application at `http://127.0.0.1:8000/`.
- Modify or extend the functionality via the `restaurant` app.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or features.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For inquiries, contact the repository owner through [GitHub](https://github.com/chandrachhetri/Django).
