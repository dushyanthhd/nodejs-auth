# nodejs-auth
A complete authentication app with login, logout, register, forget password, email verification(for added security), and access control. Can be used as starter for other Node.JS applications. using Node.js, Express, Passport, JWT, Mongoose, and more.

Web App Link
http://serene-headland-22338.herokuapp.com/

Screenshot (4)

Technologies Used
NodeJS
Express
EJS
MongoDB
Mongoose
PassportJS
JWT
Nodemailer
Prerequisites
Git
NodeJS
CLI
Installation
Clone the latest Repository
git clone https://github.com/rahulsups/nodejs-auth.git

Into the project directory
cd nodejs-auth

Installing NPM dependencies
npm install

Then simply start your app
npm start

The Server should now be running at http://localhost:3006/
Folder Structure
nodejs-auth
├── assets
│ --- ├── secure-icon.png
│ --- ├── cyber-security-icon.jpg
│ --- └── css
│ -------- └── bootstrap.min.css
├── config
│ --- ├── checkAuth.js
│ --- ├── key.js
│ --- └── passport.js
├── config
│ --- └──authController.js ├── models
│ --- └── User.js
├── node_modules
├── routes
│ --- ├── auth.js
│ --- └── index.js
├── views
│ --- ├── dash.ejs
│ --- ├── forgot.ejs
│ --- ├── layout.ejs
│ --- ├── login.ejs
│ --- ├── messages.ejs
│ --- ├── register.ejs
│ --- ├── reset.ejs
│ --- └── welcome.ejs
├── .gitignore
├── package.json
├── package-lock.json
├── README.md
└── server.js
