# Sri
#create a Django project
django-admin startproject myproject
#Navigate into the project directory
cd myproject
#create a Django app
python manage.py startapp myapp
#Add 'myapp'  to INSTALLED_APPS in myproject/settings.py
#...
INSTALLED_APPS=[
#..
'myapp'
]
#create a file myapp/views.py with the following content:
