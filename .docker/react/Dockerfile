FROM node:18-slim as build

WORKDIR /usr/src/app

ADD /home/workshop/docker-wrapper/frontend/*.json ./
RUN yarn install

RUN yarn run build
