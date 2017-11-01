![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 07: NodeJS & NPM
===

## Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[Node JS Docs](https://nodejs.org/en/)

[NPM JS Docs](https://docs.npmjs.com/)

[Express JS Docs](http://expressjs.com/en/4x/api.html)

## Configuration
_Your repository must include:_

```
07-nodejs-npm-express
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── node_modules
├── package-lock.json
├── package.json
├── public
│   ├── data
│   │   └── hackerIpsum.json
│   ├── index.html
│   ├── new.html
│   ├── scripts
│   │   ├── article.js
│   │   └── articleView.js
│   ├── styles
│   │   ├── base.css
│   │   ├── fonts
│   │   │   ├── icomoon.eot
│   │   │   ├── icomoon.svg
│   │   │   ├── icomoon.ttf
│   │   │   └── icomoon.woff
│   │   ├── icons.css
│   │   ├── layout.css
│   │   └── modules.css
│   └── vendor
│       └── styles
│           ├── default.css
│           ├── normalize.css
│           └── railscasts.css
└── server.js
```

## Feature Tasks

*As a user, I want to be able to create new articles and allow guests to retrieve those new articles.*

- Initialize the project with `npm init`, which creates `package.json` and `package-lock.json` files. Don't forget to add `node_modules` to your `.gitignore` file!
-  Use NPM to install ExpressJS, and ensure that it's been saved as a dependency in the `package.json` file.


*As a developer, I want to use the ExpressJS framework to set up a server file to handle HTTP requests and deliver responses.*

- Instantiate the ExpressJS framework, configure the `app.use` middleware to interface with the file system, configure any needed routes, and tell the server to listen for incoming requests.
- Run the server using `node server` and ensure that your app functions correctly. If you'd like to have your code live re-load the way that `live-server` did, install the NPM package `nodemon` and use that to run your server.

### Stretch Goals
*As a user, I want to access the form directly so I can easily add new articles.*

- Create a route and callback that will serve up the new.html page via a separate URI.

*As a user, I want feedback if I have made an error so that I can make sure to always access the correct URL.*

- Create a ***404*** route to handle any requests other than index.html or new.html, and deliver a 404 status message to those invalid requests.

## Documentation
_Your README.md must include:_

```md
# Project Name

**Author**: Nick Gibson, Garrett Johnson
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
This is a blog application that can now communicate with the middleware.

## Getting Started
1. Install the express package as a dependency on nodeJs
2. Include all the static resources
3. Refactor some functions into arrow functions
4. Write a new route that will redirect the user from /new to /new.html
5. Do some more refactoring

## Architecture
We used jQuery, NodeJS, WRRC and body-parse

## Change Log
11/01/2017 9:00am - Somehow we don't pull down the server.js file with all the TODO's
11/01/2017 11:00am - Finally start the ACTUAL lab
11/01/2017 11:10am - Got everything instantiated and installed
11/01/2017 11:30am - Refactor functions into arrow functions
11/01/2017 11:40am - Write a new route that will redirect the user from /new to /new.html
11/01/2017 12:00am - Add some finishing touches
-->
```
