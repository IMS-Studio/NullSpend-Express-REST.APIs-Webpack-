# NullSpender

NullSpender is an image sharing website that allows users to search, save, and
download premium stock photographs for free. Vanilla client-side technologies (HTML5, CSS3, and JavaScript) and Webpack for a bundler.

 For the back-end development, I have used Express.js for the REST-API.

 I have utilized the third-party API provided by Unsplash, which allows the application to
fetch image-related data under the hood.

For efficient website performance, I have utilized Webpack to integrate several optimization
techniques, such as file compression, code minification, and code transpilation (ES6 syntax
to ES5 syntax). Since JavaScript favors composition over inheritance, I have implemented
the factory pattern when a particular UI requires multiple functionalities. Otherwise, I have
implemented the ES6 class syntax to help manage similar UI. To reduce the total number of
DOM access, I have implemented a few DOM optimization techniques, such as
fragmentation.

Finally, I have implemented the localStorage to store saved images of a user. Since I wanted
to persist the information as long as possible, I have chosen localStorage over
sessionStorage.

NullSpender is an image sharing website that allows users to search, save, and <br/>
download premium stock photographies for free. <br/>

The website is deployed on Heroku, which can be accessed through this URL: <br/>
https://nullspender.herokuapp.com

## Prerequisites
Create a developer account for Unsplash API: <br/>
https://unsplash.com/join

## Installation:
Download Node.js v10.16.0 <br/>
https://nodejs.org/en/download/

## Running Locally:
1) Clone the project via HTTPS or SSH.

2) Navigate to the project:<br/>
<pre>cd NullSpender</pre>
3) Install the dependencies for the project:<br/>
<pre>npm install</pre>
5) Navigate to the server directory:<br/>
<pre>cd server</pre>

6) Create an .env file.

7) Add given environment variables in the .env file:
<pre>
API_KEY = Your Unsplash API key
SECRET_KEY = Your Unsplash API secret key
</pre>

8) Run the given script: <br/>
<pre>npm start</pre>

9) Navigate to http://localhost:3000

10) Enjoy the website! Royalty-free image sharing website built in pure HTML, CSS, and JavaScript (ES6)

### Author:
Kevin Romano
https://github.com/IMS-Studio
