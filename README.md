# TecShop

Live Demo: https://ahad-tecshop.herokuapp.com/

### About
***
This project was a full stack application that utilizes the MERN (MongoDB, Express, React, Node.js) stack to create a e-Commerce application (like Amazon) but exclusively for tech products. Users can sign up for an account, view products, add products to their cart, go through the full checkout process using Paypal. In addition, admin users can manage users, profiles and orders.

### Key Learnings
***
This project helped me gain experience with designing and developing a full stack project using the MERN stack. Some practical concepts I explored included ES6 syntax, Asynchronous JavaScript, creating responsive frontend views with state management using React, Bootstrap, Redux and creating a RESTful API that reads and writes data to a cloud database using Node.js, Express, MongoDB/Mongoose/Atlas, Postman and more.

### Usage
*** 
[Live Demo](https://ahad-tecshop.herokuapp.com/)

To tinker with the code and start your own localhost server, simply clone repository and then you need to set a .env file under the root folder to set up the env variables as shown below
```bash
NODE_ENV = development
PORT = 5000
MONGO_URI = <your_mongodb_uri>
JWT_SECRET = <yoursecret>
PAYPAL_CLIENT_ID = <your_paypal_client_id>
```
 and then type 
```bash
npm install
cd frontend
npm install
``` 
to install all necessary node modules as specified in package.json and then
```bash
npm run dev
```
to run both the backend (on localhost:5000) and the frontend (on localhost:3000).
