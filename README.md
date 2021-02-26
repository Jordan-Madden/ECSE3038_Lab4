# ECSE3038_Lab4
## Aim
This lab is meant to get students more accustomed to the technologies used in designing and implementing a RESTful API server using PostgreSQL.

## Requirements
You've been assign a project that will be used to manage a system that monitors the status of a set of electronically measured water tanks. The embedded circuit attached to each water tank will measure the height of the water in the tank and report on the tank's current occupancy as a percentage of its maximum capacity.
The assignment is to design a RESTful API that allows each IoT enabled water tank to interface with your server so that the measure values can be represented visually on a web page. The web page will be designed by another member of your team.
The API should also support the maintenance of a simple user profile.
The server should be able to perform the actions of a simple HTTP web server. The server should be able to perform actions on a resource such as Create, Read, Update and Delete. This is to be done without the use of a database.
The server can be implemented using any language you choose as long as it supports the requirements as they are describe below.
The server should be designed to host at least 7 specific HTTP routes. They are:
```
GET /profile
POST /profile
PATCH /profile
GET /data
POST /data
PATCH /data/:id
DELETE /data/:id
```
