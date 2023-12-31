
# Blog Project

Introduction Welcome to the Blogging Web Application! This application is built using HTML, CSS, JavaScript, and MongoDB. It allows users to create, edit, and delete blog posts.


## Screenshots


![App Screenshot1](https://github.com/abhijithca78/Blog-Project/assets/83497961/c803ed6e-c07f-4222-91f8-e4e293ca0a08)


![App Screenshot2](https://github.com/abhijithca78/Blog-Project/assets/83497961/56eb0d0e-f6d0-4523-9d61-215af4b9bb52)


## Table of Contents

- Features 
- Requirements
- Installation 
- Enviroment Variables
- Deployment
- Usage/Examples
- Dependencies


## Features

- User authentication: Users can sign up, log in, and log out.
- Create, edit, and delete blog posts.
- View blog posts.
- Responsive design for a seamless experience across devices.
- MongoDB integration for data storage.
## Requirements

- Node.js installed on your machine.
- MongoDB installed locally or a cloud-based MongoDB instance.
- Code editor of your choice (e.g., Visual Studio Code, Sublime Text).
## Installation

1 . Clone the repository:

```bash
  git clone https://github.com/abhijithca78/Blog-Project.git
```
2 . Navigate to the project directory:

```bash
  cd Blog-Project
```
3 . Install dependencies:

```bash
  npm install
```
    
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

 - `MONGODB_URI=your_mongodb_connection_string`
 - `SECRET_KEY=your_secret_key`


## Deployment

To deploy this project
Create an account and configure Cyclic with your git account:

  Cyclic : <a href="https://www.cyclic.sh/">https://www.cyclic.sh/</a>
  
  - `Add your Repository` 
  
  - `Add Environment Variables`
  
  - `Save and Deploy`



## Usage/Examples

- `After successful Deployment click on the provided link.`
  
## Demo 
<a href ="https://plum-tasty-capybara.cyclic.app/">https://plum-tasty-capybara.cyclic.app/</a>


## Dependencies

- Express: Web application framework. 
- Mongoose: MongoDB object modeling for Node.js. 
- Validator: Authentication middleware. 
- cors : A node.js package for providing Connect/Express middleware
- favicon : For generating favicons and their associated files
- bodyParser : Parse incoming req bodies in a midware before your handlers
- bcrypt : A library to help you hash passwords.
- jwt : An implementation of JSON Web Tokens.
- path : This is an exact copy of the NodeJS ’path’ module .
- fs : adds file system methods that aren't included in the native fs module
