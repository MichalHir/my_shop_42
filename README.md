# My Tennis Club Django Project

## Setup environment

1. **Create and activate a virtual environment:**
    - python -m venv venv
    - source venv\Scripts\activate
    - pip install -r requirements.txt
2. Create the database and superuser
    - python manage.py migrate
    - python manage.py createsuperuser

4. run the server
    - python manage.py runserver

5. add some products in admin or shell and navigate to 'http://127.0.0.1:8000/products/'

pip freeze > requirements.txt
Python manage.py shell


Setup environment
Create and activate a virtual environment:

python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
Create the database and superuser

python manage.py makemigrations ...
python manage.py migrate
python manage.py createsuperuser

run the server

python manage.py runserver
add some products in admin or shell and navigate to 'http://127.0.0.1:8000/products/'

michal
michal@gmail.com
1234