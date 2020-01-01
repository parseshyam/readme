# README

This README would normally document whatever steps are necessary to get your application up and running.
˜

### What is this repository for?
- Quick Summary :
  This repo is responsible for handeling all API's requests and responding for the same.
  All api's are built with express js framework (https://expressjs.com/)
- Express js Version used 4.17.1

### Requirements

- Node v8.11 +
- postgreSQL
- Express.js
- NPM v6.13.4 OR YARN 1.21.1, installed in your environement

### Prerequestics

- Setup for firebase-admin cloud messaging for sending push notifications.
- Geocoding API api key( for Geo-coder : Getting address from latitude and longitude).
- Setup for Sendgrid account to handle emailing service.

### How do I get set up ?

#### Summary of set up

Clone the repo and install the dependencies.

```
git clone https://parse_shyam@bitbucket.org/simformteam/pool-trader-backendapi.git
```

####  Dependencies

- Install all dependencies using `npm install`

####  Configurations

- Setup new `.env` file in root directory of the project.

####  Database configuration

- All configuration is done in root config dir.
- In above existing `.env` file make changes for DB key value.

####  Running Locally

- run `npm start` for running Express app in local machine

#### Deployment instructions

##### - EC2 : Create AWS EC2 instance.
```
- Take pull from the git repository 
- Setup .env in the root of the project directory.
- Create a process using pm2 sudo pm2 start index.js
- Logs: pm2 logs
- Information about the process sudo pm2 info <process id>and list all the processes sudo pm2 list
```

####  Contribution guidelines
- [Express.js](http://expressjs.com)
- [Fire Base] (https://firebase.google.com/docs)
