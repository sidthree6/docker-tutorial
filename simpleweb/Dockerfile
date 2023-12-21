# Specify base image
FROM node:14-alpine

WORKDIR /usr/app

# Copy files
COPY ./package.json ./

# Install dependencies
RUN npm install

COPY ./ ./

# Default command
CMD ["npm", "start"]