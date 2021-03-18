**# Django-project-with-delete-create-read-update-with-postgresql**
Workers' registration webapp

**clone @** 
https://github.com/Ndacyayisenga-droid/Django-project-with-delete-create-read-update-with-postgresql.git

**INSTALLATION**

clone the app
install Postgresql on your machine
configure the postgresql database according to your specifications eg password in the settings.py file
Follow the same oder of thr database but creat it in Postgresql and change the password if at all it is different or remove it if u dont have any

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'EmployeeDB',
        'USER': 'postgres',
        'PASSWORD': '0787297104',
        'HOST': 'localhost'
    }
}

crate the database in the postgresql
Run "python manage.py runserver"
