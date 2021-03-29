FROM node:alpine

RUN NODE_OPTIONS=--max_old_space_size=4096

# Run tests
WORKDIR /usr/app
COPY ./ /usr/app
RUN npm install

# Build the app
RUN npm run build
