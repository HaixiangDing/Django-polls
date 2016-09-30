# Django-polls
Django version 1.10.1 & Python version 3.5.2

Django Project: Poll

cd djangogirls

. myvene/bin/activate

LOGIN PYTHON SHELL: python manage.py shell

LOG OUT PYTHON SHELL: CONTROL+C

Back to previous level: cd ..

Get access: cd filename/foldername

Show file/folder: ls

HOW TO MAKE MODEL CHANGES:

Change your models(in models.py)
Run "python manage.py makemigrations" to create migrations for those changes
Run "python manage.py migrate" to apply thoses changes to the database
HOW TO CREATE VIRTUAL ENVIRONMENT:

mkdir djangogirls
cd djangogirls
python -m venv myvene (whatever name you apply)
~/djangogirls$ python3 -m venv myvenv (!!!)
~/djangogirls$ . myvenv/bin/activate
AFTER YOU ACTIVATE YOUR virtualenv, USING PIP TO SETUP DJANGO...

(myvenv) ~$ pip install django==1.10.1
REFERENCE:

https://docs.djangoproject.com/en/1.10/intro/
https://carolhsu.gitbooks.io/django-girls-tutorial-traditional-chiness/content/django_installation/README.html
