# Use official Node.js LTS image
FROM node:18

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Copy app source code
COPY . .

# Expose the port your app runs on (change if needed)
EXPOSE 3000

# Start the app
CMD ["node", "index.js"]
