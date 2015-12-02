# django1.8-template
This repository is for storing the template of the django project, which uses the PostgreSQL.

settings sources are from : [https://github.com/twoscoops/django-twoscoops-project](https://github.com/twoscoops/django-twoscoops-project)


# Install
Install all the modules which are needed

    pip install -r requirements/local.txt

# DB Migration
DB migration is needed before run server, without migration it is ok to be launched

    manage.py makemigrations --settings=pmodum.settings.local
    manage.py migrate --settings=pmodum.settings.local
