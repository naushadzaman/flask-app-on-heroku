heroku-flask
====================
Install Flask, the web framework, and Gunicorn, the web server.
primarily from: https://devcenter.heroku.com/articles/getting-started-with-python

Initial Setup for both AWS and Heroku 
-----
	## login to heroku 
	$ heroku login
	
	## cd to project directory 
	$ mkdir flask-project
	$ cd flask-project
	
	## setup virtualenv
	$ virtualenv venv --distribute
	$ source venv/bin/activate
	
	## install Flask - web framework and Gunicorn - web server 
	$ pip install Flask gunicorn
	
	