# Requirements
Make sure that you have the following installed:
- [node](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04) 
- npm 
- [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) and start the mongodb service with `sudo service mongod start`

## Navigate to the Client Folder 
 `cd client`

## Run the folllowing command to install the dependencies 
 `npm install`

## Run the folllowing to start the app
 `npm start`

## Open a new terminal and run the same commands in the backend folder
 `cd ../backend`

 `npm install`

 `npm start`

 ### Go ahead and add a product (note that the price field only takes a numeric input)


 # Requirements
## Make sure that you have the following installed:
    • node
    • npm
    • MongoDB and start the mongodb service with sudo service mongod start
## Navigate to the Client Folder
cd client
## Run the following command to install the dependencies
npm install
## Run the following to start the app
npm start
## Open a new terminal and run the same commands in the backend folder
cd ../backend
npm install
npm start
## Go ahead to add a product (note that the price field only takes a numeric input)with docker compose
# Instructions
    1. Clone this repository https://github.com/lawrence0580/yolo
    2. Change in to yolo directory cd yolo
    3. Run docker compose #docker-compose up --build
        ◦ You can pass -d to the above command if you want to run in detached mode
If you need to go inside a container run the following command docker exec -it <container id> /bin/bash - Run docker ps to get the container ID
To view container logs docker logs <container id>
## Yolo Application deployment to Google Kebernetes
## Project Description
To implement the orchestration concepts by hosting yolo web app project on google kubernetes engine instances.
## Live Link
The link to the live deployment to google kubernetes engine is http://34.155.46.193:3000/
## Technologies Used
Installed kubernetes tools such minikube, kubectl tools to facilitate deployment of containers to kubernetes. Installed docker. Google Cloud SDK Shell was used to push gcloud and kubectl commands.


## *****************************END**********************************
