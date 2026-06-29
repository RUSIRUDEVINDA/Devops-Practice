# get the base image
FROM node:20-alpine

#set the working directory, #this /app working directory is located inside the container, not on your local machine in
WORKDIR /app

#copy the package.json file
COPY package.json .

#install the dependencies
RUN npm install

#copy the files
COPY . .

#run the app
CMD ["npm", "start"]
