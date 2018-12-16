# Specify a base image
FROM node:alpine

# Change the current working directory
WORKDIR /usr/app

# Copy application package file and install some dependencies
COPY ./package.json ./
RUN npm install

# Copy the remaining project files
COPY ./ ./

# Default command
CMD ["npm", "start"]