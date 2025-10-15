# Use Node.js base image
FROM node:14-alpine

WORKDIR /app

# Copy package files first
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy **all other source files**
COPY . .

# Expose React default port
EXPOSE 3000

# Start React
CMD ["npm", "start"]
