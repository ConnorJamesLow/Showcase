# Features
### Fast Response
### Responsive Design

# Technologies and Tools
Proverb is a Counseling Management application built on a variation of the MEAN stack: **MongoDB**, **Express**, **React**, and **Node**.
### RESTful API with Express
I used **Postman** to test my Express API and add initial data. Postman provides tools to create collections of requests and test scripts.
![Api Collection Runner](img/api_test_suite.gif)
> Running a Postman Test suite to test a collection of API routes all at once.  

The structure of the Express backend immitates layered architecture for a loosely coupled design: my Express app routes requests to controller methods, which pass a callback through a business layer to my data layer, where the results of the asynchronous database query can be sent to the client. 
```
### Mongo Database
### React

# More content by Connor Low
I have been working on a tutorial for deploying Node.JS applications to Heroku. It includes some of the same technologies referenced here. [Click here to check it out](https://github.com/ConnorJamesLow/icc-heroku)!