FROM node:alpine

RUN NODE_OPTIONS=--max_old_space_size=4096

# Run tests
WORKDIR /usr/app

COPY ./package.json ./package-lock.json /app/
RUN npm install

COPY . /app

RUN npm run build
