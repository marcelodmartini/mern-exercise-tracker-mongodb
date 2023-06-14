MongoDB Atlas (MongoDB Atlas on Google Cloud. A fully managed, cloud-based, global MongoDB database that combines JSON-like data models, advanced search and indexing, 
and elastic scalability, while automating time-consuming administrative tasks.)

Mongoose:
Mongoose is an object-oriented data modeling (ODM) library for MongoDB and Node. js. Manages relationships between data, provides schema validation, and is used to 
translate between objects in code and the representation of those objects in MongoDB.

node -v

Create and initial react project:
npx create-react-app mern-exercise-tracker-mongodb

Create package.json and install dependecies and libs of nodjs:
npm init -y    

Install libs:
npm install express cors mongoose dotenv

Express:
Express is a compromising web framework, written in JavaScript and hosted within the NodeJS runtime environment. The module explains some of the key benefits of this framework, 
how to set up your development environment and how to perform common tasks in web development and web publishing.

Cors:
CORS is a node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options.

Dotenv:
Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment 
separate from code is based on The Twelve-Factor App methodology.

How To Restart Your Node.js Apps Automatically with nodemon
npm install -g nodemon

Star node server:
nodemon server

REACT:
    JSX (JSX stands for JavaScript XML. JSX allows us to write HTML in React. JSX makes it easier to write and add HTML in React.) 
    npm start (for react starting)          

Boostrap (is the most popular CSS Framework for developing responsive and mobile-first websites.):
npm install bootstrap

React-router-dom (React Router DOM is an npm package that enables you to implement dynamic routing in a web app. It allows you to 
display pages and allow users to navigate them. It is a fully-featured client and server-side routing library for React. React Router 
Dom is used to build single-page applications i.e. applications that have many pages or components but the page is never refreshed instead 
the content is dynamically fetched based on the URL. This process is called Routing and it is made possible with the help of React Router Dom)
npm install react-router-dom

How install datapicker react component
npm install react-datepicker

Kill port 5000
sudo kill -9 $(sudo lsof -t -i:5000)