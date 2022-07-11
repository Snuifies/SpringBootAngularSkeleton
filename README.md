# SpringBootAngularSkeleton
Skeleton to get up and running with Spring Boot and Angular

## Checkout:
* git clone https://github.com/Snuifies/SpringBootAngularSkeleton.git

## Build: 
in the SpringBootAngularSkeleton folder run 
* mvn package

### The build will
* Install node and angular dependencies by run the necessary npm commands
* package and install the frontend in the maven repository
* build and package the backend

## Testing the frontend as a standalone:
In the SpringBootAngularSkeleton/frontend folder, run
* ng serve

### in the browser navigate to http://localhost:4200
you should see the Demo Angular application

### stop the frontend app

## Testing that the backend loads the frontend:
in the SpringBootAngularSkeleton/backend/target folder run:
* java -jar backend-0.0.1-SNAPSHOT.jar

### in the browser navigate to http://localhost:8080
you should see the Demo Angular application

### stop the backend

This is the skeleton to get started.

## Addtional features to add soon
- database backend
- Rest endpoints to retrieve data from backend to frontend
- Spring Security
- PrimeFaces support for Angular (primeng, primeicons)
