# Lets Play Web Application




## Project Description
This is a webapp that allows users to find group members for different games.
Games can be pickup basketball, videogames, and dungeons and dragons.

## Tools
* Flask
	* Backend Routing using Python
* Github
	* Code repository
* Jinja
	* Frontend templating
* sqlAlchemy
	* Database
	
## Developers
* <a href="https://github.com/alexshelto">Alexander Shelton </a>  
* <a href="https://github.com/benjaminxbauer"> Ben Bauer </a>  
* <a href="https://github.com/ajstein51"> AJ Stein </a>  
* <a href="https://github.com/hunterburden"> Hunter Burden </a>

## Roles
Alex: Team Lead (float)
Ben and Hunter: Back End
AJ: Front End

## Plans for final project
We are planning on hosting this web app on a website to allow people to access it via smartphone / computer


# Documentation table of contents
- [Virtual Enviornment](#virtual-enviornment)
- [Installing](#installing-dependencies)
- [Running Locally](#running-locally)
- [Resources](#resources)


## Virtual enviornment
It is highly recomended to use a virtual machine for python  
https://virtualenv.pypa.io/en/latest/  
https://docs.python.org/3/tutorial/venv.html  
https://docs.python.org/3/library/venv.html   

## Installing dependencies
Make sure you are using python 3.x  
Activate virtual machine
```shell
$ cd Lets-Play-webapp
$ pip install -r requirements.txt
```

## Running Locally
The application itself is built in the run.py file. This line will set your run.py file up as the main file
```shell
$ export FLASK_APP=run.py
```
When running your app locally it is recomended to be in debugger mode. To put your app in debugger mode and run the web app this line can be used.
```shell
$ FLASK_DEBUG=True flask run
```
Windows Command Prompt:
```
C:\your\path>set FLASK_APP=run.py
set FLASK_DEBUG=True 
flask run
```



## Resources
<a href="https://flask.palletsprojects.com/en/1.1.x/quickstart/"> Flask Doccumentation </a>  
<a href="https://flask.palletsprojects.com/en/1.1.x/quickstart/#routing"> Flask Routing </a>  
<a href="https://flask-sqlalchemy.palletsprojects.com/en/2.x/quickstart/"> Flask with SQLAlchemy </a>  

