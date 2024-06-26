FROM node:18-slim as build

WORKDIR /usr/src/app

COPY . .
RUN yarn install

RUN yarn run build
