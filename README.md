
# Blog Project

Introduction Welcome to the Blogging Web Application! This application is built using HTML, CSS, JavaScript, and MongoDB. It allows users to create, edit, and delete blog posts.


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text="https://github.com/abhijithca78/Blog-Project/assets/83497961/4e1a4172-34a4-477b-a9cf-42667e933777")


![App Screenshot](https://ibb.co/sJkf1xh)

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

 `MONGODB_URI=your_mongodb_connection_string`
 `SECRET_KEY=your_secret_key`


## Deployment

To deploy this project
Create an account and configure Cyclic with your git account:

```bash
  Cyclic : https://www.cyclic.sh/
  Add your Repository 
  Add Environment Variables
  Save and Deploy
```


## Usage/Examples

```bash
  After successful Deployment click on the provided link.
  Example : https://plum-tasty-capybara.cyclic.app/
```


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
