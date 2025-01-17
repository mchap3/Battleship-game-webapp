# Battleship Blue Team
Blue Team's Battleship game for CSC 510 final project.

## Required Software
- [NodeJS](https://nodejs.org/en/download) (refer to npm download first)
- [MongoDB](https://www.mongodb.com/docs/manual/administration/install-community/)
- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- Mongoose: 'npm install mongoose'
- Angular: 'npm install -g @angular/cli'
- Nodemon: 'npm install nodemon'

## Required Downloadable Angular Modules
- ScrollModule: 'npm install --save @angular/cdk'
- Material for radio button: 'ng add @angular/material'
- WebSocket: 'npm i socket.io-client'


## Backend Setup
1. I believe you should be able to simple `npm install` in the root directory of the project.
2. Make sure MongoDB is installed.
3. To start backend, run: `npm start`
4. To close, run: `npm stop`

## Add Sample Posts to populate users and games and fetch them
- curl -X POST -H "Content-Type: application/json" -d '{"username": "seth"}' http://localhost:3000/users/create
- curl -X POST -H "Content-Type: application/json" -d '{"username": "seth"}' http://localhost:3000/games/create

- curl -X GET http://localhost:3000/users
- curl -X GET http://localhost:3000/games/active

## Run Frontend
1. To build: ng build
2. To run and launch: ng serve --open