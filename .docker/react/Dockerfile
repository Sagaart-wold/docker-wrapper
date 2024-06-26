FROM node:18-slim as build

WORKDIR /usr/src/app

COPY frontend/. .
RUN yarn install

RUN yarn run build
