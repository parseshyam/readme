# README

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for?

##### - Quick Summary :
- This repo is a React app for admin panel featuring all necessary actions an admin can perform by interacting with the UI.
- For State management the MobX library is used (https://mobx.js.org)
- This React app with interact with backend-app for fetching all data and rendering to admin.

### Requirements

- Node v8.11 +
- NPM v6.13.4 OR YARN 1.21.1, installed in your environement

### How do I get set up ?

#### Summary of set up

Clone the repo and install the dependencies.

```
git clone https://parse_shyam@bitbucket.org/simformteam/pool-trader-admin.git
```

####  Dependencies

- Install all dependencies using 
```bash
cd 

# If you use npm
npm install
```

####  Configurations

- Setup new `.env` file in root directory of the project.

####  Running Locally

- run `npm start` for running React app in local machine

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
- [React.js](https://reactjs.org/docs/getting-started.html)
- [MobX](https://mobx.js.org/intro/concepts.html)
