# NestJS Redis Microservices

## Prerequisite  
- Make sure you have Redis Up and running(Example using Docker `https://hub.docker.com/_/redis`)

## Running the User Service  
Inside the users folder run `npm install`  
Run users in dev mode `npm run start:dev`

## Running the Profile Service  
Inside the profiles folder run `npm install`   
Run profiles in dev mode `npm run start:dev`  

## Running the bff(backend for frontend) Service  
Inside the bff folder run `npm install`   
Run bff in dev mode `npm run start:dev` 

## Test the App  
`GET` to `http://localhost:3000/accounts`   

`POST` to `http://localhost:3000/accounts`   
```
    {
    "id": 3,
    "login": "jack",
    "name": "Jack"
    }
```

_Please do not ever use hardcoded configuration in your projects. Use at least a `.env` instead._  

Reference [Article](https://hackernoon.com/how-to-build-microservices-in-nestjs)