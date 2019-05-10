# React Crud
A React app with CRUD functions. 

This app needs to run the server to fetch the data from the MongoDB. Please check [this repository](https://github.com/kukuu/react-crud-redux/node-todo-api)
to run the server.


## Installation and usage

### Client

Install the app dependencies:
```bash
$ npm install
```
Start the application:
```bash
$ npm start
```

### Server - API

A NodeJS server with CRUD operations on MongoDB.

**You're going to need to run your mongod.exe.**

You can execute the following requests:
- GET localhost:3000/todos
- GET localhost:3000/todos/:id
- POST localhost:3000/todos
- DELETE localhost:3000/todos/:id
- PATCH localhost:3000/todos/:id

#### Full app
You can run this server and then run this [project](https://github.com/kukuu/react-crud-redux) together.

#### Installation and usage

Install the app dependencies:
```bash
$ npm install
```
Start the application:
```bash
$ npm start
```

Run the tests:
```bash
$ npm run test-watch
