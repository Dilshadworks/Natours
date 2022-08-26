### Natours

### This is a landing Page built in Sass and BEM technique. Requirment was to built this landing page in 7 - 1 layer SASS Architechture. 

#### Steps to develop Web Page:
  @Open Terminal 
    1. # install node and npm
        ## npm -v
        ## node -v
    2. # npm init => author [ghumman] => description [landing page] ==> name [project name]
    3. # npm i node-sass
    4. ### chnage "scripts" in PACKAGE.JSON File.

#### Finally PACKAGE.JSON looks like this:

#### package.json look like this
{
    "name": "booking-app",
    "version": "1.0.0",
    "description": "online booking app system",
    "main": "index.js",
    "scripts": {
        "compile:sass": "node-sass sass/main.scss css/style.css -w"
    },
    "author": "Ghumman Dilshad",
    "license": "ISC",
    "devDependencies": {
        "node-sass": "^7.0.1"
    }
}                                          
     6. ### npm run compile:sass 
     7. ### open INDEX.HTML into your browser                               
