FROM node:carbon

MAINTAINER Blair Butterworth

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./

# Install modules
RUN npm install

# Bundle app source
COPY . .

# Expose growth chart port
EXPOSE 9000

# Run application
CMD [ "npm", "start" ]
