FROM node:18-slim as build

WORKDIR /usr/src/app

ADD *.json ./
RUN yarn install

ADD ./public ./public
ADD ./src ./src