# NodeJS API RESTful Starter kit

* Objective:
I've working on the RESTful web application, and would like to practice more security in term of fetching data
from cloud server or authurised server

# Tasks to do.
- Seperate files between Server and Client 
- Create Webpage
- Login/Register Page
- Dashboard 

# How to run
- git clone https://github.com/mrtawans/nodejs-api-and-token-starter-kit.git
- git cd nodejs-api-and-token-starter-kit
- npm install
- npm run start

## Go to http://localhost:3000
* Do Fake Authencation 

## Go to http://localhost:3000/auth/tawan
* You would get generated token
* Look at src/server/routes/index.js
* Fetch data from RESTful API server

## Go to http://localhost:3000/api/city?token=__TOKEN__
* TO DO:
- POST the generated token by x-www-form-urlencoded
- Create form submit and stores token into cookies or session. 
- BOOM! you could fetch secured datas as JSON format.