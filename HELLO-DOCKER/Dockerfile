#! We are using # Use Node.js Alpine image as the base image from the DockerHub
FROM node:alpine

#! Copy all the files in the present directory to a new directory named "app" inside the container
COPY . /app 

#! Approach 1 (Run the command by giving the complete path)
# CMD node /app/app.js   

#! Approach 2 (Run the command by giving the relative path i.e set the working directory first, then run the command)
#! Set the working directory inside the container to "/app"
WORKDIR /app

#! Run the command "node app.js"
# CMD node app.js

#! Run the command to start the application
CMD ["node", "app.js"]