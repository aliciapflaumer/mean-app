# MEAN App

Teaching myself how to use Angular 2 with an Express api

Following this [helpful guide](https://scotch.io/tutorials/mean-app-with-angular-2-and-the-angular-cli) I found on the Internet.

- To start server, run `node server.js` on the command line.
  Go to localhost:3000 in the browser to view app, and localhost:3000/api to see that the api works.

# Steps

- install the angular cli with `npm install -g angular-cli` in the command line

## Create the Angular App

- `ng new mean-app`
- `ng serve`
- open `http://localhost:4200` in the browser

## Adding Express

- install Express with `npm install --save express body-parser`

- Create a file in the root of directory called `server.js` and a folder called `server`
  - Add code

- In the `server` folder create a file called `/routes/api.js`
  - Add code

- Run `ng build`

- Run `node server.js`

- `http://localhost:3000` loads the app, and `http://localhost:3000/api` shows that the express api works
