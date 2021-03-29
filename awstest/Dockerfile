FROM node:15.12.0 as node

RUN NODE_OPTIONS=--max_old_space_size=4096

# Run tests
RUN npm install

# Build the app
RUN npm run build
