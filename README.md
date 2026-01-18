Goods Store API (Express CRUD)

Project Description

This project is a simple REST API built with Node.js and Express. It simulates a small electronics store and provides CRUD operations for managing goods. Data is stored in a local JSON file (data.json).

How to Install Dependencies


Open terminal in the project folder
In terminal: npm install
In terminal:  node server.js
The server will run on: http://localhost:3000
API Routes

Demo Routes

GET / – Server test

GET /time – Returns current server time

GET /status – Returns server status

Goods CRUD Routes

GET /goods – Get all goods

POST /goods – Create a new good

PUT /goods/:id – Update a good by ID

DELETE /goods/:id – Delete a good by ID


