# Full-Stack-Development
Team ID: CRED-T8 | Team Members: Narendra Manglani & Abhishek Ranjan

Table of Contents
Objective
Introduction
Demo
Features
Built With(Tech Stack)
How to Get Started
Deployed Links
Developed By
Objective
Build a Credit Card Management system (web application) which can handle the entire lifecycle of a customer’s credit card. Functionality like adding and verifying credit card(s), fetching the credit card statement to generate a summary and extract insights and making payments for the card. The system should have a UI which gives the customers a clean interface to use.

Introduction
As an externship program we had provided a project to make a Credit Card Management System similar to CRED. We successfully build the web application as well as android application.

Demo
Below is a demo of final project.

Demo Link

GIF



Features
User can login and register using email and password.
User can add their credit card.
User can update their details in Profile section.
Same card can be added by two or more users(need authorization to do so).
User can pay bill to decrease the outstanding amount.
User can take a look at all the statements for a specific month of a year.
User will get a graphical analysis of the spendings for every month.
User will get reminders on email and phone for last 5 days of every month(he/she has an option to disable reminders).
User will get reward points for timely paying credit card dues.
User can use the reward points to buy coupons for companies like Amazon, Flipkart, Myntra, etc.
Built With
ReactJS - A JavaScript library for building user interfaces

Redux - A Predictable State Container for Javascript Apps

React-Bootstrap - Wrapper for bootstrap in ReactJS

NodeJS - It is a JavaScript runtime built on Chrome's V8 JavaScript engine.

ExpressJS - It is designed for building web applications and APIs.

MySQL - A relational database management system to store data.

Sequelize - It is a promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.

How To Get Started
Clone the repository

cd backend and create a folder named config. Inside that folder make a file named config.json

Content of config.json should be similar to this.

Note: We are using mysql as a dialect(for storing data). You can use any dialect like Postgress, MariaDB, SQLite and Microsoft SQL Server. But you have to change config.json accordingly.

{
    "development": {
      "username": "<db_user>",
      "password": "<password>",
      "database": "cred_dev",
      "host": "127.0.0.1",
      "dialect": "mysql"
    },
    "test": {
      "username": "<db_user>",
      "password": "<password>",
      "database": "cred_test",
      "host": "127.0.0.1",
      "dialect": "mysql"
    },
    "production": {
      "username": "<db_user>",
      "password": "<password>",
      "database": "cred_prod",
      "host": "127.0.0.1",
      "dialect": "mysql"
    }
  }
In backend directory create a file named .env

Content of .env should be similar to this

PORT=5000
SECRET=<YOUR_SECRET_KEY>
ENCRYPTION_KEY=<YOUR_ENCRYPTION_KEY>
TWILIO_ACCOUNT_SID=<TWILIO_ACCOUNT_SID>
TWILIO_AUTH_TOKEN=<TWILIO_AUTH_TOKEN>
TWILIO_PHONE_NO=<TWILIO_PHONE_NO>
EMAIL=<AN_EMAIl_ID>
EMAIL_PAS=<EMAIL_PASSWORD>
In backend directory run npm install.

cd frontend and create a file named .env.

Content of .env should be similar to this.

REACT_APP_BACKEND_URL_DEV=http://localhost:5000/
REACT_APP_BACKEND_URL_PROD=<BACKEND_DEPLOYED_URL>
In frontend directory run npm install

cd backend and exectute following command

npm run dev - to run server and client concurrently
npm run server - to run server standalone
npm run client - to run client standalone.
Deployed Links
Web Application
Link
Android APK
Link
Demo Account
email: cadel21249@vreagles.com
password: Temp@123
Developed By
Mandava Ravi Dharma Teja
