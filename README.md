# Blog-Project
 A Blog web application using HTML, CSS, JS, MongoDB

 
![Screenshot (29)](https://github.com/abhijithca78/Blog-Project/assets/83497961/84f6c910-5fcf-46d6-b340-f91955f47166)


![Screenshot (28)](https://github.com/abhijithca78/Blog-Project/assets/83497961/15b1afd6-18c0-4ac6-a690-e15e6f0faabd)


Introduction
Welcome to the Blogging Web Application! This application is built using HTML, CSS, JavaScript, and MongoDB. It allows users to create, edit, and delete blog posts.

Table of Contents
Features
Requirements
Installation
Usage
Folder Structure
Dependencies
Contributing
License

Features
User authentication: Users can sign up, log in, and log out.
Admin can Create, edit, and delete blog posts.
Responsive design for a seamless experience across devices.
MongoDB integration for data storage.

Requirements
Node.js installed on your machine.
MongoDB- cloud-based MongoDB instance.
Code editor of your choice (e.g., Visual Studio Code, Sublime Text).

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/blog-app.git


Navigate to the project directory:

bash
Copy code
cd blog-app


Install dependencies:

bash
Copy code
npm install


Create a .env file in the root directory and configure the following variables:

env
Copy code
PORT=3000
MONGODB_URI=your_mongodb_connection_string
SECRET_KEY=your_secret_key
Usage


Start the application:

bash
Copy code
npm start
Open your web browser and go to http://localhost:3000 to access the application.


Dependencies
Express: Web application framework.
Mongoose: MongoDB object modeling for Node.js.
Validator: Authentication middleware.
EJS: Embedded JavaScript templating.
cors
favicon
bodyParser
bcrypt
jwt
path
fs
