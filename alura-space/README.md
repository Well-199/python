python3 --version

python -m venv env

source env/bin/activate

deactivate

pip install django

pip freeze > requirements.txt

django-admin startproject config .

python manage.py startapp app

python manage.py collectstatic

sudo apt-get install libpq-dev python-dev

pip install pyscopg2

Para Linux ou se der erro no mac

pip install psycopg2-binary

python3 manage.py runserver

pip install python-dotenv
