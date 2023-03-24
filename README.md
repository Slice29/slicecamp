# Slice Camp

## Portofolio NodeJS Fullstack Application

This is a project built alongside this Udemy Course: https://www.udemy.com/course/the-web-developer-bootcamp/

The SliceCamp name is an adaptation of YelpCamp, the project developed in the later part of the Course.
After an extensive introduction into basic web Technologies (HTML,CSS,JS), I started the development of this complex web application.
The App a Yelp-like service for rating camping sites.

## The Development Stack

This web application is built in NodeJS, using Express to handle the different web routes and connection to the server.
The Mongo database is stored locally on the machine.
The HTML is generated dynamically using EJS.
The fronted uses CSS with Bootstrap 5.

## Functionalities & Plans for the future

Features that are implemented:

* Connection to the server using Express 
* Database schema 
* Randomly generated camp names using the index.js script which populates the Mongo database
* CRUD functionality using put and post requests with asynchronous operations performed on the DB
* Dynamic HTML pages with EJS

however the project is put on hold temporarily.

The course also goes into:
* Middleware
* Error Handling
* Cookies
* Authentication and Authorization
* Image Uploads
* Cluster Maps
* Deploying the project

and many more which I plan on implementing some time in the future.

## How to use the project

If you want to use the application on your machine, here are some steps to help you with the process:
1. Clone the repo locally on your machine
2. Install MongoDB https://www.mongodb.com/docs/manual/installation/
3. Start the Mongo database
4. Run Git Bash in the repo folder and install all the dependencies using NPM
5. Run app.js to make sure the connection to the server and the database is established. There are messages that confirm both the connection to the server and to the database that should be displayed in the console.
6. Run the index.js in the seeds folder to populate the Mongo database with randomly generated names for the camps
7. Run app.js again. The app should be correctly displayed on port 3000 on your local machine.
