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
	$ pip install -r requirements.txt
	
	$ foreman start
	
	$ git init
	$ git add .
	$ git commit -m "init"
	
	$ heroku create
	$ git push heroku master
	
pip install flask-login
pip install flask-openid
pip install flask-mail==0.7.6
pip install sqlalchemy==0.7.9
pip install flask-sqlalchemy==0.16
pip install sqlalchemy-migrate==0.7.2
pip install flask-whooshalchemy==0.55a
pip install flask-wtf==0.8.4
pip install pytz==2013b
pip install flask-babel==0.8
pip install flup	
