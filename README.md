# Crone.ar Backend

This project was bootstrapped with [Django](https://www.djangoproject.com/download/)

## Pre-requisites


In order to run this project, you must have these dependences installed on your OS:

  * python3
  * tkinter (python module)
  * pip (python package index)


## Pre-requisites installation
#### NOTE: This guide is intended for Linux environments, for Windows follow  [this guide.](https://developer.mozilla.org/es/docs/Learn/Server-side/Django/development_environment).

### Install Python
```sh
 sudo apt-get install python3
```


### Install tkinter
```sh
 sudo apt-get install python3-tk
```

### Update pip
```sh
 pip install --upgrade pip
```
  

### Install dependencies

```sh
 pip install -r requirements.txt
```
  

### Setup the virtual enviroment

```sh
virtualenv venv
```

###  Activate the venv

```sh 
source venv/bin/activate
```
  

###  Create database migration files

```sh 
python3 manage.py makemigrations && python3 manage.py migrate
```
 
 ## Running the project locally
 
###  Start server
  
```sh 
python manage.py runserver
```
* It runs the app in the development mode. Open http://127.0.0.1:8000 to view it in the browser.

  
## Learn More

To learn Django, check out the [Django documentation](https://docs.djangoproject.com/en/4.0/).

# ¡Happy coding!