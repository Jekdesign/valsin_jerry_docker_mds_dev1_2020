# Use a lighter version of Node as a parent image
FROM mhart/alpine-node:12

# Set the working directory to /api
WORKDIR /backend

# Copy the current directory contents into the container at /api
COPY . /backend/

# install dependencies
RUN npm install

# Make port 80 available to the world outside this container
EXPOSE 8080

# Run the app when the container launches
CMD [ "npm", "start" ]