# Setting up
- Creating the virtual environment: ```python -m venv venv```
- Activating the virtual environment
    - ```./venv/Scripts/activate``` (For Windows) 
    - ```source venv/bin/activate``` (For linux)
- Installing the requirements: ```pip install -r requirements.txt```

# Setting up database
- Run migrations on the database ```cd expense_tracker && python manage.py migrate```
- Create a superuser ```python manage.py createsuperuser```

# Running the server
- ```python manage.py runserver```