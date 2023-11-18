# Keeper App


## What is the Project

A replica of Google Keep created mainly using MERN stack. Used React functional components for styling the client side, Express and Node for setting up the backend server and MongoDB as a Database for storing title and description of the notes. Here users can add title and description of a particular note and can also delete that note.

![](https://github.com/iArpitVerma/Google-Keeper/blob/main/assets/images/initial-page.jpg)


## Technologies Used

* HTML5, CSS3, JavaScript to develop the front-end
* react.js to create the components and UI
* .jsx files to write HTML in the body of JavaScript
* Nodejs and ExpressJs for developing backend server
* MongoDB database for saving notes


## How to setup the project

* Clone the repository.
* Open it in VSCode or Sublime text editor.
* This is the frontend part of Google Keeper, to actually run it you need backend server also.
* Clone this repo 'https://github.com/iArpitVerma/Keeper-api' now.

* Keeper-api repo changes
* Open this in another window of VSCode and run 'npm init'.
* Setup your mongoDB account and in Cluster section, click on create Collections and you will get unique 'USER' and 'PASS' for that cluster, Put this in index.js on line 10 and 11.
* Now open terminal again and run 'nodemon index.js', this will start your server at 'http://localhost:5000'.

* Google Keeper repo changes
* Go to App.jsx and on line 9 Delete "https://keeper-api-azna.onrender.com" and replace it with "http://localhost:5000".
* Open Terminal and run 'npm start', this will open browser window with url "http://localhost:3000" and you will see your web app running successfully.


# How to use
* Click on "Take a note..." placeholder.
* The text area gets expanded and a **"+"** button to add the note also appears. The user now have an option to add a title as well
* When user enters something in the note and click on **"+"**, a new tile of note gets created with a delete button
* A user can also delete the note when they click on the delete button