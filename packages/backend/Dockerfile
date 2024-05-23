# Dockerfile for backend (Nest.js)
FROM node:14-alpine

WORKDIR /app

# Install dependencies
COPY packages/backend/package.json packages/backend/yarn.lock ./
RUN yarn install

# Copy source code
COPY packages/backend ./

# Build the application
RUN yarn build

# Expose the port
EXPOSE 3000

# Start the application
CMD ["yarn", "start:prod"]
