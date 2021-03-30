FROM node:alpine

# Run tests
WORKDIR /usr/app
COPY ./ /usr/app
RUN npm install

# Build the app
RUN npm run build
