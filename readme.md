
# Project Name: *Nodejs Authentication*

  

## Description: *Its my social web app.*

  

## Technologies:

*HTML
CSS/SCSS
Node.js
Express.js
Passport.js 
MongoDB
Robo3T*

## Features:
*3 types of Authentication
user profile page
home page
change password*

  

## Project Setup:

 

**Environment:** *Windows 10,*
	
**NPM:**
			

 - express
 - cookie-parser
 - express-ejs-layouts
 - express-session
 - passport
 - passport-local-strategy
 - mongoose
 - passport-google-oauth2-strategy
 - middleware
 - connect-flash
 - node-sass-middleware
 - connect-mongo
 
 
  Commands to start the server, to install node-package-manager are:
```
npm start
npm install "package-name"

```

**Other applications:**

 - Robo3T
 - chrome
 - vs code

## Step by step guide

 - create index file for the project
 - set up the directory folder structure (eg: Controllers folde)
   - Controllers folder for all controllers functions
   - routes folder for all routes
   - models folder for all models including my DB
   - views folder etc
- link the folders as required
- set up view engines
- create layouts
- create header and footer and include it to the main layout
- setup static file and create a new folder named assets
- link mongoDB
- setup user schema
- create sign in/up pages and create function in the controllers folder to render pages accordingly
- include sign-up/in form to the pages accordingly
- setup passport js
-  create express sessions authentication function
- pass user data to profile pages(the page is accessible only to the authenticated user )
- setup scss
- setup sassMiddleware
- create function to change password for authenticated users
