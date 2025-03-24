# Use Node.js LTS image
FROM node:18

# Create app directory
WORKDIR /app

# Copy and install dependencies
COPY package*.json ./
RUN npm install

# Copy app source
COPY . .

# App runs on port 3000 (change if needed)
EXPOSE 3000

# Start the service
CMD ["npm", "start"]
