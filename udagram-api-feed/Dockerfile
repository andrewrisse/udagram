FROM node:12

# Create app directory
WORKDIR /usr/src/app

# Install deps
COPY package*.json ./
RUN npm install

# Copy app source
COPY . .

# Bind port
EXPOSE 8080

# Start app
CMD ["node", "www/server.js"]
