# Use Node.js base image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json first for caching
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy source code
COPY . .

# Expose backend port
EXPOSE 5000

# Start backend
CMD ["npm", "start"]
