# Explanation
## Base Image used
FROM node:17-alpine3.12 - The image is smaller in size, takes less time to download.
## docker directive
This Dockerfile uses the FROM instruction to specify the base image for the new image we are building. In this case, the base image is node:17-alpine3.12 
The MAINTAINER instruction specifies the maintainer of the image, and the WORKDIR instruction sets the working directory for the image.
The COPY instruction copies the package.json file from the host to the specified location in the image. This file is used by the npm install command to install the app's dependencies.
The RUN instruction runs the npm install command to install the dependencies specified in the package.json file.
The COPY instruction then copies the entire app from the host to the specified location in the image.
The RUN npm run build is used to compile the project for production
Finally, the CMD instruction specifies the command to run when a container is created from this image. In this case, is ` CMD [ "serve", "-s", "build", "-l", "3000" ] ' which will start the app.
To build the image using this Dockerfile, you would run the docker build command and specify the path to the Dockerfile. For example:

docker build -t my-npm-app . 
This will build the Docker image with the specified instructions and save it with the tag my-npm-app. You can then use this image to run containers, share it with others, or push it to a Docker registry.

## dockerhub 
[lawrence client](https://hub.docker.com/r/lawrence0580/client)

[lawrence backend](https://hub.docker.com/r/lawrence0580/backend)