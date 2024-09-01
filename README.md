## Demo App - developing with Docker

This demo app shows a simple user profile app set up using 
- index.html with pure js and css styles
- nodejs backend with express module
- mongodb for data storage

## To start the application using Docker Compose

1. **Start mongodb and mongo-express**
- docker-compose -f docker-compose.yaml up

_You can access the mongo-express under localhost:8080 from your browser_

2. **in mongo-express UI - create a new database "***my-db***"**

3. **in mongo-express UI - create a new collection "***users***" in the database "***my-db***"**

4. **start node server** 
- npm install (install)
- node server.js (run)

#### To build a docker image from the application

- docker build -t my-docker-demo-app .      
    
The dot "." at the end of the command denotes location of the Dockerfile.

## Docker Desktop with mongodb and mongo-express containers 



## Edit User Profile



## User interface of Docker database mongo-express