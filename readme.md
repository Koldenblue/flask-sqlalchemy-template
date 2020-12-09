# Flask with SQLAlchemy Template

This app provides starter files for a webpage using Flask and a SQL database with the SQLAlchemy ORM. User authentication functionality is included and handled through SQL. A seeder file can by run with the command "python seeder.py". This file will drop the database if it exists and create it from scratch, with a single user with username "1" and password "1".

CSS is handled through Sass. A Sass watch script is available with "npm run watch-sass", although it may have to be customized depending on your Sass installation.

Flask can be run in with the command "npm run watch". The website will be viewable at "localhost:5000" once the Flask server is started. This command assumes nodemon is installed, o that the server may automatically restart as files are updated. Flask, of course, must also be installed. If nodemon is not installed, it may be installed using the command "npm install nodemon". Flask may be installed through pip. Alternatively, Flask may be run without the auto-updating functionality of nodemon by using the command "flask run".