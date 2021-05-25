## Screenshots

![Screenshot1](/screenshots/screen1.png)

# Post Cards

A Full satck App allowing users to post cards to represent meaningfull instances in their lives.

## OverView

An Application implementing React, Node.js, Express & MongoDB Allowing users to post cards to the website representing meaningful moments to them.

## Demo

Live demo is available here: **[Demo](https://jolly-montalcini-ba5221.netlify.app/)**

Setup:

- run `npm install && npm start` for both client and server side to start the app

## Features

- Client

  - React client with functional components
  - Redux state management with Thunk for async actions
  - CSS agnostic, so you don't waste your time replacing my CSS framework with yours
  - Home, Menu, , Login, Register and contact pages
  - Protected routes with Higher order components
  - MaterialUI components used with correspondive styling
  - Axos Fetch Operations Recieved by Bakcend.

- Server

  - CRUD operations implemented with Express
  - Add , create , delete and like Posts.
  - Submit pictures with posts.
  - MongoDB Model and schema.

## How to Run

- Change the Fetch API in client/src/api/index.js
- Change the CONNECTION_URL for MongoDB link in server/index.js
- cd client && npm start
- cd server && npm start
