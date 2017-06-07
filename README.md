# ORCS
Online Character Sheet v0.1.0

ORCS stands for Online Roleplaying Character Sheets, it is basically an online database that allows people to download, edit and store their character sheets electronically.

Version 1 is quite simple, just a login facility, select a sheet, or create a new one, and then basic CRUD operations on the data. The tasks you will be able to perform are:

C - Create new character sheet (will require internet access to create new sheets)
R - Read character sheet from database or local storage if offline when loading
U - Update character sheet
D - Delete character.



#Technology

The system will be built using ASP.Net MVC 5 web api on the back end, and AngularJS on the front end. There are a few reasons for choosing this blend of front and back end technology which I won't go in to here, but initially we will be using Angular 4, and MVC5. We might change to .net core and Angular 4 at some point in the future, but for now we're gonna stick to these programming languages.

The database will run on a Mongo noSQL database. This is not the ideal database for MVC (SQLlite would be a better choice) however I am planning on creating a nodeJS version of the server API further down the line, and mongoDB would be a much better fit for nodeJS.

The front end will be running as a single page application (SPA) - this will then allow me to publish the front end as a mobile app using phonegap.




-----------------------------------------------

Change log

v0.1.0 - 7/6/2017
First Commit - This is a training application using the github extention to visual studio 2017. 

test changes in test branch 1
