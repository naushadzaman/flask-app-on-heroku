heroku-flask
====================
Install Flask, the web framework, and Gunicorn, the web server.
primarily from: https://devcenter.heroku.com/articles/getting-started-with-python and 
http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

Initial Setup for both AWS and Heroku 
-----
	## clone flask-app on heroku codes  
	$ git clone https://github.com/naushadzaman/flask-app-on-heroku
	
	## login to heroku 
	$ heroku login
	
	## cd to project directory 
	$ mkdir flask-project
	$ cd flask-project
	
	## setup virtualenv
	$ virtualenv venv --distribute
	$ source venv/bin/activate
	
	## install pre-requisites 
	$ cp ../flask-app-on-heroku/requirements.txt .
	$ pip install -r requirements.txt

	## copy all files 
	$ cp ../flask-app-on-heroku/Procfile .
	$ cp -r ../flask-app-on-heroku/app .
	$ cp ../flask-app-on-heroku/config.py .
	$ cp -r ../flask-app-on-heroku/tmp/ .

	
	$ foreman start
	
	$ git init
	$ git add .
	$ git commit -m "init"
	
	$ heroku create
	$ git push heroku master
	
