# E-commerce-APP-Using-MERN

The steps that I follow it for building this project

1. Install tools
2. create a ReactAPP by typing : "npx create-react-app frontend " and making some changes in the App.js file and the index.css for styling the header an the main those are my first steps.
3. add the data the images that related tothe products tat we need to dislay it into the main page of products
4. Add Routing
   4.1 npm i react router-dom
   4.2 create route for home screen
   4.3 create router for product screen
5. Actually Rightnow I'm deciding to create the node js server side of our e-commerce website
   5.1 run npm init in root folder
   5.2 update packkage.json set type: module
   5.3 add .js to imports
   5.4 create server.js
   5.5 add start command as node backend/server.js
   5.6 require express
   5.7 create route for / return backend is ready.
   5.8 move product.js from frontend to backend
   5.9 create route for /api/products
   5.10 return products
   5.11 run npm start
6. Fetch Products From Backend
   6.1 Set Proxy in package.jsoon
   6.2 npm install axios
   6.3 use state hook
   6.4 use effect hook
   6.5 use reducer hook
7. Right now we will change useState by useReduce (Manage State By Reducer Hook)
   7.1 define reducer
   7.2 update fetch data
   7.3 get state from useReducer
8. Add Bootstrap UI framework
   8.1 npm install react-bootstrap bootstrap
   8.2 update App.js
9. In this step We will create the products Details Screen
   9.1 Fetch product from backend
   9.2 create 3 columns for image, info and action
10. Create Loding and Message Component
    10.1 create loading Component
    10.2 use spinner component
    10.3 create message component
    10.4 create utils.js to define getError function
