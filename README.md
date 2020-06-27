# Project Name
> djangoNote

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [design](#design)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
<!-- Add more general information about project. What the purpose of the project is? Motivation? -->
    DjangoNote is a webapp running on the server side which function as a notetaking app.
    It is my first software project and it currently run successfully on my computer port, I plan to upload it to   
heroku server, and add more functionalities on it.

## Screenshots
<!-- ![Example screenshot](./img/screenshot.png) -->
![logInPage](./img/logInPage.png)
![homePage](./img/homePage.png)
![notePage](./img/notePage.png)
![noteEditPage](./img/noteEditPage.png)
![tagEditPage](./img/tagEditPage.png)
## Technologies
* Tech 1 - version 1.0
* Tech 2 - version 2.0
* Tech 3 - version 3.0
## design
<!-- ![designDiagram](./img/OMD.png) -->
the design concept is very simple. there are only two models.
* note - the note has label, body, and tags.
* tag - the tag has label and can be used to sort the notes.

## Setup
<!-- Describe how to install / setup your local environement / add link to demo version. -->
`pip install -r requirements.txt`

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py createsuperuser`
then input user name and password (the password may not show on the screen, just input it via keyboard)

`python manage.py runserver`
the app is running on your computer
<!-- ## Code Examples
Show examples of usage: -->
## Features
List of features ready and TODOs for future development
* Awesome feature 1
* Awesome feature 2
* Awesome feature 3

To-do list:
* Wow improvement to be done 1
* Wow improvement to be done 2

## Status
Project is: _in progress_, _finished_, _no longer continue_ and why?

## Inspiration
Add here credits. Project inspired by..., based on...

## Contact
Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!