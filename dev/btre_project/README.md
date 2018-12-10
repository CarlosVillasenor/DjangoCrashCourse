# Virtual environment

## Check Python version

$ python --version

## Create a virtual environment in Python 3 with the environment name of env

$ virtualenv -p python3 env

## Validate that environment is installed with python3

$ ls env/lib

## Activate the environment

$ source env/bin/activate

## Deactivate the environment

$ deactivate

# Django

## Install Django

1.- Run your virtual environment
2.- $ pip install Django

# Django help

$ django-admin help

# Create start project

$ django-admin startproject btre .

# Run server

$ python manage.py runserver