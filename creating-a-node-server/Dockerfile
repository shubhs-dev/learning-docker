# Specify a base image
FROM node:alpine

# Specify work directory to avoid files being copied to the root folder
WORKDIR /usr/app

# Copy build files to the container
COPY ./ ./
# First argument in the above command is the source path relative to build context and second argument is location inside the container

# Install some dependencies
RUN npm install

# Default command
CMD ["npm", "start"]

