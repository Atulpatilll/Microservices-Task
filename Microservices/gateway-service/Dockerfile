FROM node:18-alpine

WORKDIR /app

# Copy dependency manifests
COPY package*.json ./

# Install dependencies
RUN npm install --production

# Copy application source code
COPY . .

# Expose Gateway Service port
EXPOSE 3003

# Start command
CMD ["node", "app.js"]
