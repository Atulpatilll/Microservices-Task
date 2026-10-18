FROM node:18-alpine

WORKDIR /app

# Copy package dependency manifests
COPY package*.json ./

# Install dependencies
RUN npm install --production

# Copy application source code
COPY . .

# Expose User Service port
EXPOSE 3000

# Start command
CMD ["npm", "start"]
