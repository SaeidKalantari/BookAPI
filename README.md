# Build and sell your own Python API $$$ (super easy!) - By Saeid Kalantari


## Table of Contents

   * [Introduction](#introduction)
      * [Pages](#pages)
      * [CSS](#css)
   * [Application](#Application)
      * [Links](#links)
      * [Scripts](#Scripts)
   * [API](#API)
   * [Contributors](#contributors)



## Introduction
My name is Saeid Kalantari. In this project, we use Flask, SQL, and a PostgresSQL Database. I used Bulma to design the overall theme of the webpage and then customized it based on the project requirements. 
YouTube video Link: https://youtu.be/jFuctL-wsCo
### Pages
There are one main page in the template folder: 1. index.html (Home).
There is a (2.) base.html file that consists of the navbar of the pages, and some components that will run in all pages.
In order to run this project you need to navigate to the project folder and run:

"set FLASK_APP=application.py" and
"DATABASE_URL=...

in the terminal.

### CSS
I used Bulma open source CSS framework for this project to make the website look nicer.

## Application
In this project, I used links and scripts to change the UI and UX of the web pages.
### Links
1. Bulma
### Scripts
1. import.py: This file imports all the provided book that (the csv file) into the database
2. Application.py: is the main application that includes all the routes and functionalities.

## API
The "@app.route("/api/isbn")" line is for the visitors to search for the books and get the data using the websites API.

## Contributors
Saeid Kalantari - Canada 3-12-2022

