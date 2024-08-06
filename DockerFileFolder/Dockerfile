# Use the official Node.js image from Docker Hub
FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Install a simple HTTP server
RUN npm install -g http-server

# Create a simple index.html file
RUN echo '<html><body><h1>Hello, World!</h1></body></html>' > index.html

# Serve the index.html file on port 3000
CMD ["http-server", "-p", "3000"]
