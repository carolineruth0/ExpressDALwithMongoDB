# ExpressDALwithMongoDB

Description:
This project is for running a potential real world example of an Express DAL using MongoDB and Docker. It also requires Robo 3T and is a good way to learn this software.

Installation:
1. run "git clone https://github.com/carolineruth0/ExpressDALwithMongoDB.git"
2. make sure Docker, Mongo, and Robo 3T are installed.
3. cd into ExpresswithMongoDB directory and run "npm install"
4. run "npm install mongodb"
5. start mongo and docker applications
6. run "docker run -p 27017:27017 --name badbank -d mongo"
7. start Robo 3T and connect to localhost:27017
8. run "node index.js"
9. example of adding user (peter), email (peter@mit.edu), and password(secret)
   type this in a browser - localhost:3000/account/create/peter/peter@mit.edu/secret
10. type "localhost:3000/account/all" to view all users added

Technology used: computer, Mongo, Docker, VS Code, Robo 3T

Features: Adding/viewing users via web browser
To Add: Adding/viewing users via command line

"license": "MIT"

![DAL with MongoDB](https://github.com/carolineruth0/ExpressDALwithMongoDB/assets/146399653/52e98231-aed7-44df-a8ae-9022ea172ab9)
