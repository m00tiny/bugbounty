# BugBounty Web App


### Introduction

This web application is built with Flask, a web Python framework based on Jinja:
[Flask official web site](http://flask.pocoo.org/ "Flask's Homepage").

### About the project

The web app's goal is to help BugBounty Hunters to manage their BugBounties and TODO list.

### Depedencies


1. Pip - [Pip web site](https://pip.pypa.io/en/stable/installing/ "Pip's Homepage")
	```bash
	cd /tmp/
	wget https://bootstrap.pypa.io/get-pip.py
	python get-pip.py
	rm get-pip.py
	```
1. Flask python library
	```bash
	pip install flask
	```

### Download

* Download project from github *

	```bash
	git clone https://github.com/sokaRepo/bugbounty.git
	```

### Run WebApp

	```bash
	cd bugbounty/
	export FLASK_APP=app.py
	flask run
	```