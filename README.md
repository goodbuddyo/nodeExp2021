# nodeExp2021

Pluralsight tutorial 
Building Web Applications with Node.js and Express
by Jonathan Mills
https://app.pluralsight.com/library/courses/nodejs-express-web-applications-building/

How to build from scratch  routing, databases, and third-party APIs in Node.js and Express.

Remember to update package.json
"ejs": "^3.1.8",
 "express": "4.18.2",



cd directory

	nvm install ‑‑lts 
	npm init
	npm install express
create file  app.js
	const express = require('express');
	const app = express();

	app.get('/', (req, res) => {
	  res.send('Hello from my app');
	});

	app.listen(3000, ()=>{
		console.log(‘listening on port 3000’);
	});

	app.listen(PORT, () => {
	  debug(`listening on port ${chalk.green(PORT)}`);
	});

const chalk = require('chalk');
const debug = require('debug')('app');
const morgan = require('morgan');
const path = require('path');

npm install
npm audit fix (Updates nodemon, suggests express update)
npm start
http://localhost:4000/







