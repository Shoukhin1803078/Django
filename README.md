# virtual environment create kore Django kivabe install diye first project run korbo 

Microsoft Windows [Version 10.0.19045.3803]
(c) Microsoft Corporation. All rights reserved.

C:\Users\User>mkdir django_practice

C:\Users\User>cd django_practice

C:\Users\User\django_practice>python -m venv env

C:\Users\User\django_practice>env\Sripts\activate
The system cannot find the path specified.

C:\Users\User\django_practice>env\Scripts\activate

(env) C:\Users\User\django_practice>pip install django
Collecting django
  Obtaining dependency information for django from https://files.pythonhosted.org/packages/ba/c7/61b02c0ef9e129080a8c2bffefb3cb2b9ddddece4c44dc473c1c4f0647c1/Django-5.0-py3-none-any.whl.metadata
  Using cached Django-5.0-py3-none-any.whl.metadata (4.1 kB)
Collecting asgiref>=3.7.0 (from django)
  Obtaining dependency information for asgiref>=3.7.0 from https://files.pythonhosted.org/packages/9b/80/b9051a4a07ad231558fcd8ffc89232711b4e618c15cb7a392a17384bbeef/asgiref-3.7.2-py3-none-any.whl.metadata
  Using cached asgiref-3.7.2-py3-none-any.whl.metadata (9.2 kB)
Collecting sqlparse>=0.3.1 (from django)
  Using cached sqlparse-0.4.4-py3-none-any.whl (41 kB)
Collecting tzdata (from django)
  Using cached tzdata-2023.3-py2.py3-none-any.whl (341 kB)
Using cached Django-5.0-py3-none-any.whl (8.1 MB)
Using cached asgiref-3.7.2-py3-none-any.whl (24 kB)
Installing collected packages: tzdata, sqlparse, asgiref, django
Successfully installed asgiref-3.7.2 django-5.0 sqlparse-0.4.4 tzdata-2023.3

[notice] A new release of pip is available: 23.2.1 -> 23.3.2
[notice] To update, run: python.exe -m pip install --upgrade pip

(env) C:\Users\User\django_practice>django-admin startproject first

(env) C:\Users\User\django_practice>cd first

(env) C:\Users\User\django_practice\first>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
December 26, 2023 - 13:37:03
Django version 5.0, using settings 'first.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
