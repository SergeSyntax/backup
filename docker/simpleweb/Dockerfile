# Spesify a base image
FROM node:alpine

# WORKDIR /usr/app
WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm","start"]