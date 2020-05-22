# django-template
This repository is for storing the template of the django project, which uses the PostgreSQL.

settings sources are from : [https://github.com/twoscoops/django-twoscoops-project](https://github.com/twoscoops/django-twoscoops-project)


# Install
Install all the modules which are needed

    pip install -r requirements/local.txt

# Change the project name
You can chnage the project name with the script, rename_newtemp_app.py. This script changes all the prjoect name strings in the .py files to <new poject_name>

	rename_newtemp_app.py <new_project_name>


# DB Migration
Windows batch exists to migrate. To use this you should change the path of the batch file, migrate.bat

    .\tools\activate.bat
    .\tools\migrate.bat
    
