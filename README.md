# contactsapp
Python Django is used for creating this project.
Open the project in Pycharm or any other software,

Here "contacts" is our projectname
and "app" is our appname

==> RUN XXAMP and START APACHE, MYSQL
==> CREATE A DATABASE IN MYSQL NAMED 'phonebook'

DATABASE CONFIGURATION (XXAMP..)
Database = Mysql (changed database configuration in "contacts/settings.py")(default database is mysqlite3)
=========================
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'phonebook'
        'USER': 'root',
        'PASSWORD': '',
        'HOST': 'localhost',   # Or an IP Address that your DB is hosted on
        'PORT': '3306',
    }
}
=========================
DatabaseName = phonebook
Table_Name = contacts

AFTER CREATING A DATABASE IN MYSQL , open terminal
==>python manage.py makemigrations
==>python manage.py migrate


Here all Templates belongs to "Templates" Directory
[
homepage.html = HomePage 
signin.html = LoginPage
signup.html = Registration
]

CSS files belongs to "contactapp/static/css/<css_files>"

==>To run Project
>python manage.py runserver
