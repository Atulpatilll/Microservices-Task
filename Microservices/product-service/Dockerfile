FROM node:18-alpine

WORKDIR /app

# Copy dependency manifests
COPY package*.json ./

# Install dependencies
RUN npm install --production

# Copy application source code
COPY . .

# Expose Product Service port
EXPOSE 3001

# Start command
CMD ["npm", "start"]
