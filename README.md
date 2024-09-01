## Demo App - developing with Docker

This demo app shows a simple user profile app set up using 
- index.html with pure js and css styles
- nodejs backend with express module
- mongodb for data storage accessed with Docker

All components are docker-based.

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
<img width="600" alt="docker-desktop" src="https://github.com/user-attachments/assets/a84a09a1-8198-4f5f-9649-d514b823a538">

## Edit User Profile
<img width="200" alt="user-profile" src="https://github.com/user-attachments/assets/5a9eb13e-7980-4218-8b84-5f70a5e4013d">

## User interface of Docker database mongo-express
<img width="600" alt="mongo-express" src="https://github.com/user-attachments/assets/75abc499-92e8-4101-a0ba-b85cbc543e8c">
