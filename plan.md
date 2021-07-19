#POSTMAN

#Firstly we will do npm setup for this app
npm init -y

#We need to install few dependencies

1.Axios :It is a library which is used to make requests to an API, return data from the API, and then do things with that data in our React application. Axios is a very popular (over 78k stars on Github) HTTP client, which allows us to make HTTP requests from the browser. Axios is a promise-based library used with Node.

 npm i axios  


2 Dev  dependency called snowpack dev - Snowpack's dev server is an instant dev environment for unbundled development. The dev server will build a file only when it's requested by the browser. That means that Snowpack can start up instantly (usually in <50ms) and scale to infinitely large projects without slowing down.

npm i --save-dev snowpack

3 Bootstrap :Sleek, intuitive, and powerful front-end framework for faster and easier web development.

npm i bootstrap

4 Popper.js is a dependency of Bootstrap 4 which is used for showing popups. It is a peer dependency of bootstrap meaning it is something that bootstrap requires but doesn't include with itself when installed. So to install popper.js run
npm install popper.js --save

It is setup as a peer dependency because some people just use the css of Bootstrap without the javascript. jQuery and popper.js are the peer dependencies which needs to be installed separately. If you require the javascript of Bootstrap you need to install jQuery and popper.js alongside Bootstrap 4.

5 Bootstrap 5 requires "Popper.js Core", not Popper.js. You should run this instead:
npm install @popperjs/core --save


#Add  start script in package.json for snowpack dev it will startup development version of our application

#Add index.html page 


#Add script.js

#Run using npm start
