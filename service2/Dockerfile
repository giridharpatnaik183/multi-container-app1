# Use a base image suitable for your application (e.g., Node.js, etc.)
FROM node:14

# Set the working directory inside the container
WORKDIR /app

# Copy the application code into the container
COPY . /app

# Install dependencies (if any)
RUN npm install

# Specify the command to run your application
CMD ["node", "main.js"]

