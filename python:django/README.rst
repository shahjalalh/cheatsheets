===============
Python / Django
===============

git:
----
    ::

    $ git status
    $ git config --global user.name "Your Name"
    $ git config --global user.email you@example.com
    $ git remote add origin https://github.com/<your-github-username>/my-first-blog.git
    $ git push -u origin master


    ::

    $ git config credential.helper store
    $ git push http://example.com/repo.git

        Username: <type your username>

        Password: <type your password>
    
    
    [several days later]
    
    ::

    $ git push http://example.com/repo.git
    
    [your credentials are used automatically]


===============


Install Python:
---------------
    Install Python and PIP
    ::
    
    $ pip install virtualenv

Python
======
    ::

    $ mkdir project_name
    $ cd project_name
    $ virtualenv project_name
    $ cd project_name
    $ source bin/activate
    $ deactivate


===============


Django New:
-----------
    ::
    
    $ pip install django
    $ python
    
    >>> import django
    >>> django.VERSION
    
    ::

    $ django-admin startproject mysite
    $ cd mysite
    $ python manage.py migrate
    $ python manage.py runserver
    $ python manage.py runserver 0.0.0.0:8001
    $ python manage.py startapp app_name
    $ Create model
    $ python manage.py makemigrations app_name
    $ python manage.py sqlmigrate app_name 0001
    $ python manage.py migrate
    $ python manage.py createsuperuser
    
    Browse http://127.0.0.1:8001/admin/



    ::

    python manage.py shell




===============


Python/ Django Old Project:
---------------------------
    ::
    
    $ mkdir project_name
    $ cd project_name
    $ virtualenv project_name
    $ cd project_name
    $ source bin/activate
    $ pip install -r requirements.txt


===============


Sample Project Layout:
----------------------
project_name/
    .gitignores

    docs/

    README.rst

    requirements.txt

    manage.py

    static/

    project_name/

        __init__.py
        	settings.py

        	urls.py

        	wsgi.py

    app_name/
    	__init__.py

    	admin.py

    	apps.py

    	forms.py

    	migrations/

    	models.py

    	templates/

    		base/

    	tests.py

    	urls.py

    	views.py