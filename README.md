# ShopMe
A simple demo catalog web application with Google OAuth Store and query data using an SQL database
API JSON endpoints for all catalog data.  Project was deployed to a Apache 2.


### Hosting
The project was deployed to an Amazon Lightsail server running Apache 2.4.18 on Ubuntu 16.04-i386.

## Python Requirements

Python 2.7.11 was used to develop the web server

## Other Requirements
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
