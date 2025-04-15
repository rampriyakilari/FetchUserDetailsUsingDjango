C:\Users\student\Documents\Full Stack>django-admin startproject myapp

C:\Users\student\Documents\Full Stack>cd myapp

C:\Users\student\Documents\Full Stack\myapp>python manage.py startapp app

C:\Users\student\Documents\Full Stack\myapp>code .

C:\Users\student\Documents\Full Stack\myapp>pip install djangorestframework

C:\Users\student\Documents\Full Stack\myapp>python manage.py makemigrations
Migrations for 'app':
  app\migrations\0001_initial.py
    + Create model StudentModel

C:\Users\student\Documents\Full Stack\myapp>python manage.py migrate
Operations to perform:
  Apply all migrations: admin, app, auth, contenttypes, sessions
Running migrations:
  Applying contenttypes.0001_initial... OK
  Applying auth.0001_initial... OK
  Applying admin.0001_initial... OK
  Applying admin.0002_logentry_remove_auto_add... OK
  Applying admin.0003_logentry_add_action_flag_choices... OK
  Applying app.0001_initial... OK
  Applying contenttypes.0002_remove_content_type_name... OK
  Applying auth.0002_alter_permission_name_max_length... OK
  Applying auth.0003_alter_user_email_max_length... OK
  Applying auth.0004_alter_user_username_opts... OK
  Applying auth.0005_alter_user_last_login_null... OK
  Applying auth.0006_require_contenttypes_0002... OK
  Applying auth.0007_alter_validators_add_error_messages... OK
  Applying auth.0008_alter_user_username_max_length... OK
  Applying auth.0009_alter_user_last_name_max_length... OK
  Applying auth.0010_alter_group_name_max_length... OK
  Applying auth.0011_update_proxy_permissions... OK
  Applying auth.0012_alter_user_first_name_max_length... OK
  Applying sessions.0001_initial... OK

C:\Users\student\Documents\Full Stack\myapp>python manage.py createsuperuser
Username (leave blank to use 'student'): priya
Email address: priya@gmail.com
Password:
Password (again):
This password is too short. It must contain at least 8 characters.
This password is too common.
This password is entirely numeric.
Bypass password validation and create user anyway? [y/N]: y
Superuser created successfully.

C:\Users\student\Documents\Full Stack\myapp>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
April 15, 2025 - 12:24:41
Django version 5.2, using settings 'myapp.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
