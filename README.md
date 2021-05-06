# My first Nodejs app
## STEPS:
  1. Install all dependencies.
  2. Clone the repository.
  3. Run the app with pm2.
  4. Check it in the localhost.

#### STEP 1: 
  1. Follow the steps in the [LINK](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04) to install Nodejs and npm in your linux machine.
  2. Install PM2 using the following command `sudo npm install pm2`
  3. Install Git using the following command `sudo apt-get install git`
#### STEP 2:
  1. Clone the repository `$ git clone https://github.com/Bala-ganesh/First-nodejs-app.git`
  2. go to the respective directory where you have file my-njs-app.js
#### STEP 3:
  Run the app with PM2 to make it run continuously in the server 
  `pm2 start my-njs-app.js`
#### STEP 4:
  Run the following command to check the local host `curl localhost:8080` in our case the port is 8080.
