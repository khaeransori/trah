# Dockerfile for frontend (Next.js)
FROM node:14-alpine AS builder

WORKDIR /app

# Install dependencies
COPY packages/frontend/package.json packages/frontend/yarn.lock ./
RUN yarn install

# Copy source code
COPY packages/frontend ./

# Build the application
RUN yarn build

# Production image
FROM node:14-alpine AS production

WORKDIR /app

COPY --from=builder /app/.next ./.next
COPY --from=builder /app/public ./public
COPY --from=builder /app/package.json ./package.json
COPY --from=builder /app/next.config.mjs ./next.config.mjs

RUN yarn install --production

# Expose the port
EXPOSE 3000

# Start the application
CMD ["yarn", "start"]
