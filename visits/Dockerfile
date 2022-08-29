# Specify a base image
FROM node:alpine

# Set up a working dir..
WORKDIR '/app'

# To use image cache
COPY package.json .

# Install some depenendencies
RUN npm install

# To copy the rest of the source code
COPY . .

# Default command to start up the server
CMD ["npm", "start"]
