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
	$ cd flask-app-on-heroku/
	
	## setup virtualenv
	$ virtualenv venv --distribute
	$ source venv/bin/activate
	
	## install pre-requisites 
	$ pip install -r requirements.txt

	$ foreman start
	
	$ git add .
	$ git commit -m "init"
	
	$ heroku create
	$ git push heroku master
	
	try: 
	http://your-app-name.herokuapp.com/ and 
	http://your-app-name.herokuapp.com/input
