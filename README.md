# surveys-managment
this is survey management build by python 
here just install all feature 
Install Python and dependencies
This tutorial was created using Python 3.6. If you don't have a working Python install (or this project isn't working on your normal install), you can install Anaconda and run

$ conda create -n djangosurvey-env python=3.6
$ source activate djangosurvey-env
To install dependencies, run:

$ pip install -r requrements.txt
Database updates
When updating models for this app, make sure to run the following to update the schema:

$ python manage.py makemigrations polls
$ python manage.py migrate
The first command creates the migrations for changes to models.py. The second applies those migrations.

Testing and conventions
Testing and linting are implemented using pytest and flake8. Since this is not needed for the actual app, you'll have to run the following to install dev requirements:

$ pip install -r dev-requrements.txt
Any committed code should pass all tests, which are run with

$ pytest
Also, all committed code should pass basic PEP8 and linting requirements, which is verified using:
