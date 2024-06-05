# Ecommerce Backend 
This repository contains the backend part of the Ecommerce project. The backend is responsible for handling server-side logic, 
API endpoints, and database interactions.It is built using modern web development technologies and frameworks to provide a robust and scalable backend infrastructure.

# Deployment        
The Backend part of the project is deployed on render.com , You can visit the live application [here](https://ecommerce-frontend-build.vercel.app/).

# Tech Stack
<p style="line-height: 2;">
Node.js : A JavaScript runtime environment for building server-side applications    <br>
        
Express.js : A minimal and flexible Node.js web application framework.   <br> 

Postman : A collaboration platform for API development and testing    <br>

TypeScript : A typed superset of JavaScript that compiles to plain JavaScript.    <br>

Multer : A middleware for handling multipart/form-data, primarily used for file uploads    <br>

MongoDB : A NoSQL database for storing and managing data    <br>

Stripe : A payment processing platform for online transactions  <br>

Cloudinary :  Media management for web applications.
</p>


 # Installation and Setup
<p style="line-height: 2;">
--> Install Dependencies        <br>
        
To install the necessary dependencies, run the following command : 
<code>npm install</code>
</p>

<p style="line-height: 2;">
--> Run the Application        <br>
        
To build and run the application in development mode, use the following command : 
<code>npm run build</code>
</p>

# Environment Variables
To configure the application, create a <code>.env</code> file in the root directory and add the following environment variables to use the app:       

<p style="line-height: 2.5;">
  
PORT= <code>4000 or any</code>        <br>
        
MONGO_URI= <code>mongodb://localhost:27017/ecommerce</code>        <br>

STRIPE_KEY = <code>your_stripe_secret_key</code>        <br>

PRODUCT_PER_PAGE = <code>8 or any</code>        <br>

CLOUDINARY_CLOUD_NAME = <code>your_Cloudinary name/id</code>        <br>

CLOUDINARY_API_KEY = <code>your_Cloudinary_API_KEY</code>       <br> 

CLOUDINARY_API_SECRET = <code>your_Cloudinary_API_Secret</code>        <br>

Replace the placeholder values with your actual Firebase and Stripe configuration details.
</p>

# Frontend Repository
The frontend part of this Ecommerce project provides the user interface and handles client-side logic,  
It is built with React.js, Redux Toolkit, RTK Query, and TypeScript.  
You can find the frontend repository [here](https://github.com/NuancedNickel/Ecommerce-Frontend_Build).
