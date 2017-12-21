# ShopMe
A simple demo catalog web application with Google OAuth
Store and query data using an SQL database
API JSON endpoints for all catalog data

Matt Bladek


## Dependencies of Software and Libraries Used
The application was developed using Vagrant 2.0.1 and Virtual Box virtual environment 2.3.5
virtualizing Ubuntu 16.04-i386


* Python 2.7.11 was used in development
List of requirements is as follows: 
Flask==0.12.2
Flask-HTTPAuth==3.2.3
Flask-Login==0.1.3
Flask-SQLAlchemy==2.3.0
html5lib==1.0b10
httplib2==0.10.3
Jinja2==2.9.6
MarkupSafe==1.0
oauth2client==4.1.2
pep8==1.7.1
psycopg2==2.7.3.1
pycodestyle==2.3.1
pyparsing==2.2.0
redis==2.10.6
requests==2.18.4
SQLAlchemy==1.1.14
urllib3==1.22
webencodings==0.5.1
Werkzeug==0.12.2

* Bootstrap
	- HTML, CSS library
* Jquery - Javascript library utilized for API calls more specifically the AJAX library for asynchronous calls
* Google API - OAuth2 - Used for authentication and authorization

## Files
The following are the project files for the successful execution of the webserver.
* database_setup.py
Initializes a local SQL database and provides functionality for JSON API endpoints for our data

* application.py
The main python web server provides all routing, authentication, and CRUD functionality.

* client_secrets.json (not included)
Contains the information needed for Google API OAuth2 to authenticate sessions

* html
The html, css, and js for the project is contained the templates and static folders.

### Hosting
The project was deployed to an Amazon Lightsail server at: 

http://ec2-34-208-123-72.us-west-2.compute.amazonaws.com/

or

http://34.208.123.72/
