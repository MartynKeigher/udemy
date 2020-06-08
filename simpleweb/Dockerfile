# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some deps.
COPY ./package.json ./
RUN npm install 
COPY ./ ./

#Setup default command
CMD ["npm", "start"]