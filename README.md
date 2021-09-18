# Stripe demo using prebuilt checkout and using React and Node Express

## Basic instructions

Clone repo

From a terminal window 

`cd client`

`npm install`

`cd server`

`npm install`

## Stripe Setup

Update server.js file with your own Stripe key

`const stripe = require('stripe')('YOUR_SK_TEST_KEY_GOES_HERE')`

In the `client` directory, run `npm start` to run the client app in development mode.

In the `server` directory, run `npm run server:dev` to run the server in development mode.

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
