# User Registration Form Web App
###### This repository contains the code for a simple user registration form web application. Users can input their name, age, email, phone number, gender, and password to register. Upon successful registration, users are redirected to a confirmation page.

__________________

### Files Overview:
###### index.html
This file contains the HTML structure for the registration form. It includes input fields for name, age, email, phone number, gender, and password, along with a submit button.

###### signup_successful.html
This HTML file is displayed after successful registration. It likely contains a confirmation message or additional instructions for the user.

###### style.css
The CSS file defines the styles for the HTML elements used in the registration form and the success page. It controls the layout and appearance of the form and success message.

###### index.js
This JavaScript file contains the backend logic using the Express framework to handle form submissions and interact with a MongoDB database. 

###### package.json
This JSON file contains project metadata, dependencies, and scripts. It specifies required Node.js packages like Express, body-parser, and Mongoose for the application to function.
____________________

### Here's a summary of its functionalities:

###### Express Setup: Sets up an Express app instance and configures middleware for parsing form data and serving static files.
###### Mongoose Connection: Connects to a MongoDB database using Mongoose and handles connection errors and success messages.
###### Sign Up Route: Defines a POST route handler for form submission, retrieves form data, stores it in the MongoDB database, and redirects to the success page.
###### Root Route: Defines a GET route handler for the root path to redirect users to the registration form.
_____________________


### Getting Started:
###### Clone the repository to your local machine.
###### Install dependencies using npm install.
###### Set up a MongoDB database and update the connection string in index.js.
###### Start the server using npm start.
###### Access the application in your browser at http://localhost:3000.
________________
### Dependencies:
###### Express: Fast, unopinionated, minimalist web framework for Node.js.
###### body-parser: Node.js body parsing middleware.
###### Mongoose: MongoDB object modeling for Node.js.
_______________________
### License:
###### This project is licensed under the MIT License.
