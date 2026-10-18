FROM node:18-alpine

WORKDIR /app

# Copy dependency manifests
COPY package*.json ./

# Install dependencies
RUN npm install --production

# Copy application source code
COPY . .

# Expose Order Service port
EXPOSE 3002

# Start command
CMD ["npm", "start"]
