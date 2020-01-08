# Django Polls app

This is the django polls app as documented on https://docs.djangoproject.com/en/3.0/intro/

# Installation

Clone this directory using

```git clone https://github.com/gursahani/django-polls-app.git```

Next create a virtual environment using 

```python3 -m venv venv ```

and then make sure to install the requirements:

```pip install -r requirements.txt```

# Run

Check to see if the database models are created and run the server

```
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
```

You should now be able to view the app on http://localhost:8000/