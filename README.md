# node-microservice
Node microservice example
## Creating Microservices with Node.js
In this example, we’re going to create a microservice using Node.js which connects to an external API.

The requirement for this service is to accept two Zip Codes and return the distance between them in miles.

## Initial Steps
Have Node.js installed
Run npm init in the root folder for the project. Express and Require that can be installed like this:
```
$ npm install express request --save
```
## Execution 
```
$ npm start
```
## Web API used in application
File `api/service/distance.js` web api key can be taken [here](https://www.zipcodeapi.com/)
