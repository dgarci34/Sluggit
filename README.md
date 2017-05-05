## Getting Started in Development Mode:
1. Clone the repo: `https://github.com/cgradwohl/Sluggit.git`

2. `$ cd Sluggit`

3. Make sure you have [npm](https://www.npmjs.com/) and [node](https://nodejs.org/en/) installed. Make sure you have [mongodb](https://www.mongodb.com/) installed.

4. `$ npm install` to install dependancies.

5. Start a local mongoDB instance `$ mongod`

6. `$ npm start` for a dev backend server.

7. Navigate to `http://localhost:3000/` to make sure server app is working.

8. `$ cd angular-src`

9. make sure you have the dependancies installed `$ npm install`

10. from the `/angular-src` directory build the app `$ ng build` , this will bundle and compile the app into the public directory.

11. from the `/angular-src` directory run `$ ng serve` to start the local angular server.

12.  Navigate to `http://localhost:4200/` to see front end app.


TLDR:

1. `$ npm install`

2. `$ npm start`

3. `$ cd angular-src && npm install`

4. `$ ng build`

5. `$ ng serve`



## Commit and Push Procedure:
The app is served via the express server. Our server serves the `/public` directory (take a look at line 40 in `server.js`). To update your changes in the github repo:

1. Run `$ git pull` make sure you have the most current version and resolve merge conflicts.
2. Make sure your did step 1!
3. build the app into the public directory by running `$ ng build` from the `/angular-src` directory
4. commit your code changes AND the entire `/public` directory
5. `$ git push`



## Front End Resources We Used
1. easy custom bootstrap themes --> https://bootswatch.com/
2. simple bootstrap template --> http://getbootstrap.com/examples/starter-template/

## Known Bugs
currently bug free :) on 4/26/2017   


## Deployment Info
We deployed our app with heroku.

Run `ng build` to build the project into the public folder. (Used to deploy to heroku)

live url: https://sluggit.herokuapp.com/

## Features/Product Ideas:

This is a blog post web application similar to sites like reddit, medium and stack overflow.

Application includes user profiles, friend requests, blog posts, topic search, user feed,
blog likes and user reputation.  
Content will be recommended via user feed, based on likes AND various CS topics: (ML, AI, web development, NLP, iot, programming languages, etc.).
Users public feed will deliver relevant content based on users behavior, as well as new topics the user hasn't previously seen. 	
Includes clustering algorithm to recommend content, in browser code editor for sharing/ running code snippets.# blog-clone web application


## Code scaffolding

Run `ng g component <component-name>` to generate a new component.


## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
