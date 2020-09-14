# 66erCMS

This will be a new backend for the 66er

## Developer installation guide:

 - Install latest python 3.8.x https://www.python.org/downloads/
 - Install pipenv https://docs.pipenv.org/
 - Install PostgreSQL https://www.postgresql.org/download/
 - Install https://www.pgadmin.org/
 - Start up pgAdmin and create a user with all privileges called `sixtysix` and a database called `sixtysix`
 - clone this repository, navigate into folder sixtysix and run `./manage.py migate`
 - create a superuser wiht `./manage.py createsuperuser`
 - Run `./manage.py runserver` and go to http://localhost:8000/admin
 - Done :-D

## Useful links
 - https://docs.wagtail.io/en/stable/topics/index.html --> Wagtail Docs
 - https://www.youtube.com/watch?v=xUWd3o6z2bk --> demo app for headless development using Vue.js
 - https://gitlab.com/thelabnyc/angular-wagtail/blob/master/README.md --> angular template helping integration of Wagtail